<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import ComponentNavbar from './components/ComponentNavbar.vue';
import ComponentFooter from './components/ComponentFooter.vue';

</script>

<template>
  <div class="container-main">
    <header class="container-header">
      <ComponentNavbar />
    </header>
  
    <main class="content-main">
      <RouterView />
    </main>
  
    <div>
      <ComponentFooter />
    </div>
  </div>
</template>

<style scoped>

.container-main {
  background-image: linear-gradient(to left, #FFFFFF 60%, #D6D6D6);
}

@media screen and (max-width: 575px) {
  .content-main {
    padding: 0 20px;
  }
}

@media screen and (max-width: 991px) {

  .container-main {
    background-image: linear-gradient(to top, #FFFFFF 20%, #D6D6D6);
  }

  .content-main {
    padding-top: 50px;
  }

}
</style>
