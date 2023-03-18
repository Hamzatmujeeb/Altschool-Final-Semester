<script>

</script>

<template>
      <aside>
       <div class="profile">
        <img src="@/assets/image/avartar.png" alt="Profile Picture">
        <h3>Hamzat Mujeeb</h3>
       <button class="edit-profile"><i class="fas fa-edit"></i>Edit Profile</button>
        <ul>
        <li>Followers500</li>
        <li>Following250</li>
      </ul>
    </div>
  </aside>
</template>

<style scoped>
aside {
  width: 200px;
  padding: 20px;
  right:1700px;
  top: 170px;
}

aside .profile {
  text-align: right;
}

aside .profile img {
  width: 300px;
  border-radius: 50%;
  margin-bottom: 10px;
  background: none;
}

aside .profile h3 {
  font-size: 18px;
  margin: 0;
}

aside .profile  ul {
  display: flex;
  list-style-type: none;
  margin: 0;
  padding: 0;
}

aside .profile ul li {
  margin-bottom: 15px;
  font-size: 15px;
  margin:auto 3px auto;
  padding: 2px;
  font-weight: 300;
  line-height: normal;
  padding: 10px;
}
.edit-profile {
  background-color: #e1e3e1;
  color: #000;
  border: none; 
  width: 300px;
  padding: 10px 10px;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
}

.edit-profile:hover {
  background-color: #Cfcfc9;
}

.edit-profile i {
  margin-right: 5px;
}
</style>