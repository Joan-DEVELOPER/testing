<script setup>
import { ref } from 'vue'
import HeaderComponent from './HeaderComponent.vue'

let number = ref(0) // Actualitza la variable automaticament

setInterval(() => {
  number.value++
}, 2000)
</script>

<template>
  <h1 class="title">Hola a todos</h1>
  <h2>{{ number }}</h2>
  <HeaderComponent></HeaderComponent>
</template>

<style scoped>
/*scoped hace el estilo único de esta pagina-- >*/
.title {
  background-color: blue;
  color: white;
}
</style>
