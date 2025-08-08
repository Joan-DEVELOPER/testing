<script setup></script>

<template>
  <header>
    <nav>
      <ul>
        <li><a href="">Home</a></li>
        <li><a href="">Blog</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
/*scoped hace el estilo único de esta pagina-- >*/
ul {
  background-color: transparent;
  color: white;
  display: flex;
  gap: 30px;
  text-decoration: none;
}

li {
  list-style-type: none;
}

li,
a {
  color: black;
  text-decoration: none;
}
</style>
