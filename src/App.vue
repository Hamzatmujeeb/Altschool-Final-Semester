<script setup>
import Header from './components/Header.vue';
import Profile from './components/Profile.vue';
import Main from './components/Down-Header.vue';
import Search from './components/Repository-search.vue';
import Section from './components/Section.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <div class="container">
    <Header />
     <Profile />
     <Main />
     <Search />
     <Section/>
     <Footer />
  </div>
</template>

<style scoped>
    .container{
       padding:0;
       margin: 0;
    }
</style>
