<script setup>
import { ref } from 'vue'

const number = ref(0)

const addOne = () => {
  number.value++
}
</script>

<template>
  <h1>{{ number }}</h1>
  <button @click="addOne">Pulsame</button>
</template>

<style scoped>
/*scoped hace el estilo único de esta pagina-- >*/
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;700&display=swap');

* {
  font-family: Rubik;
}

h1 {
  outline: auto;
  margin: 5px;
  padding: 3px 15px;
}

button {
  background-color: rgb(0, 136, 255);
  color: white;
  outline: auto;
  padding: 10px;
  margin-left: 10px;
  border-radius: 5px;
}
</style>
