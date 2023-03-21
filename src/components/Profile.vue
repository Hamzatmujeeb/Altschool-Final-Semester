<script>

</script>

<template>
<div class="profile">
  <div class="avatar">
  <img src="@/assets/image/avartar.png" alt="Profile picture">
  </div>
  <h1>Hamzat Mujeeb</h1>
  <div class="edit-button">
    <button>Edit Profile</button>
  </div>
  <div class="follower-count">
    <p>Followers</p>
    <span>100</span>
    <p>Followers</p>
    <span>100</span>
  </div>
</div>
</template>

<style scoped>
.profile {
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin:40px 0px 40px ;
}

.avatar img {
  width: 300px;
  height: 270px;
  border-radius: 50%;
  object-fit: cover;
  object-position: center;
}

.follower-count {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 27px 10px 0 10px;
}

.follower-count p {
  margin: 10px;
}

.follower-count span {
  font-size: 1rem;
  font-weight:200;
}

.edit-button {
  margin-top: 20px;
}

.edit-button button {
  padding: 10px 20px;
  background-color: #ddd;
  width: 260px;
  color: #000;
  font-size: 1rem;
  font-weight: bold;
  border-radius: 10px;
  border: none;
  cursor: pointer;
}

.edit-button button:hover {
  background-color: #f1f3f5;
}

</style>