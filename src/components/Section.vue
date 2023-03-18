<script>
  
</script>

<template>
   <section class="repositories">
    <hr />
  <h2>QR-CODE</h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
  <h2>sunnyside </h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
  <h2>My-Website </h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
  <h2>Landing-page </h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
  <h2>AltschoolExamsProject </h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
  <h2>calculator </h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
  <h2>QR-CODE</h2>
  <div class="buttons">
    <button class="public-button">Public</button>
    <button class="star-button">Star</button>
    <div class="filters">
     <select id="type-select">
      <option value="all"></option>
      <option value="public">Public</option>
      <option value="private">Private</option>
    </select>
    </div>
  </div>
  <hr />
</section>
</template>

<style>
 .repositories {
  margin-top: 20px;
  right: 2390px;
  top: 250px;
}

.repositories h2 {
  font-size: 24px;
  font-weight: bold;
  right:950px;
  top: 20px;
  color: #0366d6;
  font-size:20px;
  font-weight: 700;
}

.repositories .buttons {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.repositories .buttons button {
  padding: 8px 16px;
  border: none;
  border-radius: 6px;
  font-size: 14px;
  font-weight: bold;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
}

.repositories .buttons button:hover {
  background-color: #ebeff5;
}

.repositories .buttons .public-button {
  background-color: #f5f7fa;
  color: #0366d6;
  border-radius:22px;
  font-size:10px;
  top:-15px;
  right:750px;
}

.repositories .buttons .star-button {
  color: #000;
  left:-600px;
}

.repositories .filters {
  display: flex;
  align-items: center;
  margin-bottom: 16px;
}

.repositories .filters label {
  margin-right: 8px;
  font-size: 14px;
}

.repositories .filters select {
  padding: 5px;
  top: 5px;
  border: none;
  left: -1000px;
  border-radius: 6px;
  font-size: 14px;
  cursor: pointer;
  width:45px;
  height: 30px;
  transition: all 0.2s ease-in-out;
  background:#ebeff5;
}

.repositories .filters select:hover {
  background-color: #ebeff5;
}

.repositories .filters select:focus {
  outline: none;
  box-shadow: 0 0 0 2px #0366d6;
}

hr{
 width: 1000px;
 right: 980px;
}
</style>