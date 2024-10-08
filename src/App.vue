<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import ComponentNavbar from './components/ComponentNavbar.vue';

</script>

<template>
  <header>
    <ComponentNavbar />
  </header>

  <main>
    <RouterView />
  </main>
</template>

<style scoped>

.container-div {
  background-image: linear-gradient(to left, #FFFFFF 60%, #D6D6D6);
}

@media screen and (max-width: 767px) {

  .container-div {
    background-image: linear-gradient(to top, #FFFFFF 20%, #D6D6D6);
  }
}

</style>
