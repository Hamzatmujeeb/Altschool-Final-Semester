<script>

</script>

<template>
 <footer>
  <nav>
     <ul>
        <li><a href="#">Pull Requests</a></li>
        <li><a href="#">Issues</a></li>
        <li><a href="#">Marketplace</a></li>
        <li><a href="#">Explore</a></li>
     </ul>
  </nav>

 </footer>
</template>
 
<style scoped>
  footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding:20px;
  background-color:#fff;
  border-bottom: 1px solid #ddd;
  width: 1000px;
  top:300px;
  top: 500px;
  right:3000px;
}


nav ul {
  display: flex;
  list-style-type: none;
  margin: 10px;
  padding: 10px;
}

nav ul li {
  right: 740px;
  margin: 20px;
}

nav ul li:last-child {
  margin-right: 0;
}

nav ul li a {
  color: white;
  text-decoration: none;
  display: flex;
  align-items: center;
  font-size: 14px;
}

nav ul li a i {
  margin-left: 5px;
}

footer ul {
    display: flex;
    list-style-type: none;
    margin: 0;
    padding: 0;
    top: 100px;
}

footer  ul li {
  right: 940px;
  margin: 10px;
}

footer ul li a {
  color: #000;
  text-decoration: none;
  display: flex;
  align-items: center;
  font-size: 14px;
}
</style>