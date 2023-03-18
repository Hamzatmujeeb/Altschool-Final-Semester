<script>

</script>

<template>
  <hr />
 <div class="search-container">
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
</template>

<style scoped>
   
/* Style for the search container */
.search-container {
  display: flex;
  align-items: center;
  top: -30px;
  right: 2500px;
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
  margin-right: 7px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 14px;
}

/* Style for the search select elements */
.search-container select {
  padding: 8px;
  margin: 5px;
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

.sort-button{
        top: 2px;
        left: -10px;
}
.search-container button:hover {
  background-color: #2c974b;
}

/* Style for the "New" button */
.search-container .new-repo {
  background-color: #2c974b;
  color: white;
  border: none;
  bottom: 78px;
  left: 930px;
  padding: 8px 12px;
  border-radius: 5px;
  font-size: 14px;
  cursor: pointer;
  margin-left: 10px;
}

.search-container .new-repo:hover {
  background-color: #2c974b;
}
</style>