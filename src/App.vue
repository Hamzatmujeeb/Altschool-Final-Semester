<script setup>
import Header from './components/Header.vue';
import Profile from './components/Profile.vue';
import Search from './components/Repository-search.vue';
import Section from './components/Section.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <body>
   <Header />
    <Profile />
     <Search />
     <Section/>
     <Footer />
  </body>
</template>

<style scoped>
      *{
        padding: 0;
        margin: 0;
        box-sizing: border-box;
      }
</style>
