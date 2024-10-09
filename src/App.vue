<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import ComponentNavbar from './components/ComponentNavbar.vue';

</script>

<template>
  <header class="container-header">
    <ComponentNavbar />
  </header>

  <main class="container-main">
    <RouterView />
  </main>
</template>

<style scoped>

.container-header {
  background-image: linear-gradient(to left, #FFFFFF 60%, #D6D6D6);
}

.container-main {
  background-image: linear-gradient(to left, #FFFFFF 60%, #D6D6D6);
}

@media screen and (max-width: 575px) {
  .container-main {
    padding: 0 20px;
  }
}

@media screen and (max-width: 991px) {

  .container-header {
    background: #D6D6D6;
  }

  .container-main {
    background-image: linear-gradient(to top, #FFFFFF 20%, #D6D6D6);
    padding-top: 50px;
  }

}
</style>
