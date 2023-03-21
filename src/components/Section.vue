<script>
  import axios from 'axios';
  
  export default {
    data() {
      return {
        repositories: [],
        loading: false,
        error: null,
        page: 1,
        perPage: 10,
        hasMorePages: false,
      };
    },
    methods: {
      loadRepositories() {
        this.loading = true;
        axios
          .get(`https://api.github.com/users/Hamzatmujeeb/repos?page=${this.page}&per_page=${this.perPage}`)
          .then(response => {
            this.repositories = response.data;
            this.hasMorePages = response.headers.link.includes('rel="next"');
          })
          .catch(error => {
            this.error = error.message;
          })
          .finally(() => {
            this.loading = false;
          });
      },
      loadMore() {
        this.page++;
        this.loadRepositories();
      },
    },
    mounted() {
      this.loadRepositories();
    },
  };
</script>

<template>
   <section class="repositories">
      <ul>
        <li v-for="repo in repositories" :key="repo.id">
            <div>
          <button>star</button> 
           <select>
             <option></option>
           </select> <hr />
            </div> 
          <router-link :to="'/repo/' + repo.name">{{ repo.name }}</router-link>
        </li> 
      </ul>
      <div v-if="loading">Loading...</div>
      <div v-else-if="error">{{ error }}</div>
      <button v-if="hasMorePages" @click="loadMore()">Load more</button>
  
</section>
</template>

<style>
     .repositories{
          position: absolute;
          top: 10px;
          padding:40px;
          margin:290px;
          
     }

     li{
        padding-top: 10px;
        color: #2596be;
        font-size: 30px;
        list-style: none;
        top:-50px;
        padding-bottom: 20px;
     }

     .public{
            position: absolute;
            width: 60px;
            border-radius: 25px;
            border: none;
            top: -50px;
            right: 10px;
     }

     hr{
        width: 1000px;
     }
</style>