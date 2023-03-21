<script>
   
</script>

<template>
  <div id="app">
    <div class="header">
      <div class="logo">
        <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub logo">
      </div>
      <div class="search">
        <input type="text" placeholder="Search or jump to...">
      </div>
      <div class="nav">
        <a href="#">Pull requests</a>
        <a href="#">Issues</a>
        <a href="#">Marketplace</a>
        <a href="#">Explore</a>
      </div>
    </div>
    </div>
    
</template>

<style scoped>
 .header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 1515px;
  height: 100px;
  background-color: #24292e;
  color: #fff;
  padding: 19px;
  right: 190px;
}

.header .logo img {
  height: 30px;
}

.header .search input {
  padding: 5px 10px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
}

.header .nav {
  display: flex;
}

.header .nav a {
  color: #fff;
  text-decoration: none;
  right:690px;
  font-size: 16px;
  margin: 8px;
}

.header .search input {
  padding: 5px 10px;
  margin-right:700px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  width: 400px;
  background-color: #24292e;
  border:1px solid #fff;
}


</style>