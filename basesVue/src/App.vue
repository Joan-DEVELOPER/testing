<script setup>
import { ref } from 'vue'
import HeaderComponent from './HeaderComponent.vue'
import Eventos from './eventos.vue'

let number = ref(0) // Actualitza la variable automaticament

/*setInterval(() => {
  number.value++
}, 1000)*/
</script>

<template>
  <h1 class="title">TCG Market</h1>
  <h2>{{ number }}</h2>
  <HeaderComponent></HeaderComponent>
  <Eventos></Eventos>
</template>

<style scoped>
/*scoped hace el estilo único de esta pagina-- >*/
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;700&display=swap');

* {
  font-family: Rubik;
}

.title {
  background-color: blue;
  color: white;
}
</style>
