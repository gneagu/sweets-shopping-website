<template>
  <div class="main">
    <div class="container">
      <PageHeader />
    </div>
    <div class="container">
      <RouterView />
    </div>
  </div>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import PageHeader from './components/PageHeader.vue'
</script>

<style scoped>
.main {
  width: 100%;
  justify-content: center;
}

header {
  width: 100%;
  line-height: 1.5;
  max-height: 100px;
}

@media (min-width: 1200px) {
  .container {
    width: 1200px;
  }
}
</style>
