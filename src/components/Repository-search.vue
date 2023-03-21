<script>

</script>

<template>
 <div class="search-container">
   <div class="search">
  <form action="#" method="get">
    <input type="text" placeholder="Find a repository" name="search">
    <select name="type">
      <option value="All">All</option>
      <option value="Public">Public</option>
      <option value="Private">Private</option>
    </select>
    <select name="language">
      <option value="All">Languages</option>
      <option value="JavaScript">JavaScript</option>
      <option value="HTML">HTML</option>
      <option value="CSS">CSS</option>
    </select>
    <select name="sort" class="sort-button">
      <option value="Best match">Sort</option>
      <option value="Most stars">Most stars</option>
      <option value="Fewest stars">Fewest stars</option>
      <option value="Most forks">Most forks</option>
      <option value="Fewest forks">Fewest forks</option>
    </select>
    <button type="submit" class="new-repo">New</button>
  </form>
  </div>
</div>
</template>

<style scoped>
   
/* Style for the search container */
.search-container {
    position: absolute;
     display: flex;
    align-items: center;
  top: 250px;
  right: 300px;
}

.search{
    top: 29px;
}
/* Style for the search form */
.search-container form {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

/* Style for the search input */
.search-container input[type="text"] {
  width: 600px;
  padding: 8px;
  margin-left:0px;
  top: -90px;
  right:-290px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 14px;
}

/* Style for the search select elements */
.search-container select {
  padding: 5px;
  margin: 6px;
  width: 100px;
  height: 33px;
  right: -300px;
  top:-90px;
  background: hwb(0 96% 3%);
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 14px;

}

/* Style for the search button */
.search-container button {
  background-color: #2ea44f;
  color: white;
  border: none;
  padding: 8px 12px;
  border-radius: 5px;
  font-size: 14px;
  margin: 40px;
  cursor: pointer;
}

.search-container button:hover {
  background-color: #2c974b;
  margin: 80px;
}

/* Style for the "New" button */
.search-container .new-repo {
  background-color: #2c974b;
  color: white;
  border: none;
  padding: 8px 12px;
  border-radius: 5px;
  font-size: 14px;
  cursor: pointer;
  margin: 60px;
   top:-190px;
  right: -1200px;
}

.search-container .new-repo:hover {
  background-color: #2c974b;
}
</style>