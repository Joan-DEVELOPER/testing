<script setup lang="ts"></script>

<template>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
  />
  <div class="header">
    <h1>minago</h1>

    <div class="searchBar">
      <input type="text" placeholder="Search for a product" />
      <select name="category" id="category">
        <i class="fa-solid fa-caret-down"></i>
        <option value="">All categories</option>
        <option value="">Clothing</option>
        <option value="">Electronics</option>
        <option value=""></option>
        <option value=""></option>
        <option value=""></option>
      </select>
      <button><i class="fa-solid fa-magnifying-glass"></i></button>
    </div>
  </div>

  <div class="navigation">
    <button class="section">Home</button>
    <button class="section">Products</button>
    <button class="section">Categories</button>
    <button class="section">Pages</button>
    <button class="section">Campaign</button>
    <button class="section">Offer</button>
    <button class="section">Blog</button>
    <button class="section">Review</button>
    <button class="section">Flash Sale</button>
    <button class="section">Contact Us</button>
  </div>

  <div class="promotion">
    <div class="promoCard">
      <img
        src="https://media.ambito.com/p/78cfb2963ae3d070339d361607822a0d/adjuntos/239/imagenes/040/281/0040281423/1200x675/smart/black-fridaywebp.png"
        alt="black friday banner"
      />
    </div>
  </div>
  <div class="products">
    <div class="product">Product 1</div>
    <div class="product">Product 1</div>
    <div class="product">Product 1</div>
    <div class="product">Product 1</div>
  </div>
</template>

<style scoped>
body {
  margin: 0;
  padding: 0;
}

@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

* {
  font-family: 'Roboto';
}

.header {
  background-color: white;
  color: black;
  height: 15vh;
  margin: 0;
  padding: 2px;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
  border-bottom: 1px solid black;
}

.header h1 {
  text-transform: uppercase;
  font-weight: bold;
  font-size: 20px;
}

.header a {
  color: aquamarine;
  text-decoration: none;
}

.searchBar {
  margin: 0;
  padding: 0px;
}

.searchBar input,
select {
  margin-right: 10px;
  padding: 5px;
}

.searchBar option {
  background-color: white;
}

.searchBar option:hover {
  background-color: lightskyblue;
}

.searchBar button {
  background-color: rgb(88, 187, 249);
  font-weight: bold;
  padding: 6px;
  border: 1px solid black;
  border-radius: 5px;
}

.navigation {
  display: flex; /* Agrega flexbox */
  justify-content: center; /* Centra los elementos horizontalmente */
  background-color: rgb(50, 171, 246);
  width: 100%;
}

.navigation button {
  margin: 2px;
  padding: 7px;
  background-color: transparent;
  border: none;
  color: white;
}

.promoCard {
  justify-self: center;
  outline: auto;
  width: 30%;
  float: right;
  margin-right: 10px;
  margin-top: 10px;
}

.promoCard img {
  width: 100%;
  outline: auto;
  align-self: center;
}

.products {
  margin-top: 10px;
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  justify-self: center;
}

.product {
  outline: auto;
  width: 22.8%;
  margin: 10px;
  padding: 10px;
}
</style>
