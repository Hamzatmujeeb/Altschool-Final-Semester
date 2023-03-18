<script>
   
</script>

<template>
  <header>
  <div class="logo">
    <img src="@/assets/image/github.png" alt="Logo">
  </div>
  <div class="searches">
        <input type="text" placeholder="Search or jump to...">
        <button type="submit">/</button>
      </div>
  <nav>
     <ul>
        <li><a href="#">Pull Requests</a></li>
        <li><a href="#">Issues</a></li>
        <li><a href="#">Marketplace</a></li>
        <li><a href="#">Explore</a></li>
     </ul>
  </nav>
</header>

<main>
    <ul>
        <li><a href="#">Overview <i class="fas fa-caret-down"></i></a></li>
        <li><a href="#">Repositories <i class="fas fa-caret-down"></i></a></li>
        <li><a href="#">Projects <i class="fas fa-caret-down"></i></a></li>
        <li><a href="#">Packages <i class="fas fa-caret-down"></i></a></li>
        <li><a href="#">Stars <i class="fas fa-caret-down"></i></a></li>
      </ul>
</main>

</template>

<style scoped>
  header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding:0;
  background-color: #010;
  border-bottom: 1px solid #ddd;
  width: 1700px;
  right:0px;
  height: 70px;
  left: 30px;

}

.logo {
  display: flex;
  align-items: center;
}

.logo img {
  width: 80px;
  height: 70px;
  left: 20px;
}

.logo h1 {
  font-size: 2rem;
  margin: 0;
}

.searches input[type="text"] {
  padding: 5px;
  border-radius: 5px;
  border: 1px solid #ddd;
  background: #000;
  font-size:15px;
  right: 370px;
  width: 250px;
  height: 42px;
  color: #fff;
}

.searches button[type="submit"] {
  padding: 5px 15px;
  border-radius: 5px;
  border: 1px solid #ddd;
  background-color: #000;
  color: white;
  font-size: 13px;
  right: 380px;
  margin-left: -47px;
  cursor: pointer;
  width:10px;
  height: 30px;
}

nav ul {
  display: flex;
  list-style-type: none;
  margin: 10px;
  padding: 10px;
}

nav ul li {
  right: 740px;
  margin: 10px;
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

main ul {
    display: flex;
    list-style-type: none;
    margin: 0;
    padding: 0;
    top: 100px;
}

main  ul li {
  right: 940px;
  margin: 10px;
}

main ul li a {
  color: #000;
  text-decoration: none;
  display: flex;
  align-items: center;
  font-size: 14px;
}


</style>