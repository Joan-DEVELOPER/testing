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
.title {
  background-color: blue;
  color: white;
}
</style>
