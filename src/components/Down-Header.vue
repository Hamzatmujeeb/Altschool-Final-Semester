<script>

</script>

<template>
    <main>
        <ul>
            <li><a href="#">Overview <i class="fas fa-caret-down"></i></a></li>
            <li><a href="#">Repositories <i class="fas fa-caret-down"></i></a></li>
            <li><a href="#">Projects <i class="fas fa-caret-down"></i></a></li>
            <li><a href="#">Packages <i class="fas fa-caret-down"></i></a></li>
            <li><a href="#">Stars <i class="fas fa-caret-down"></i></a></li>
          </ul>
    </main>
    <hr />
</template>

<style>
 main ul {
    display: flex;
    list-style-type: none;
    margin: 0;
    padding: 0;
    top: 100px;
}

main  ul li {
  margin: 10px;
  left: 600px;
  top:-100px;
}

main ul li a {
  color: #000;
  text-decoration: none;
  display: flex;
  align-items: center;
  font-size: 14px;
}

hr{
    width:1000%;
}
</style>
