<script setup lang="ts">
import CategorySet from '@/components/CategorySet.vue'
import InTextBanner from '@/components/InTextBanner.vue'
</script>

<template>
  <div class="home">
    <div class="about">
      <h1>This is the main asdasdadadasasasd</h1>
    </div>
    <div class="status">
      <CategorySet />
    </div>
    <div>
      <InTextBanner />
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100px;
    display: flex;
    align-items: center;
  }

  .home {
    /* background-color: rgba(253, 242, 249, 0.897); */
    background-color: #f7f7f7;
  }

  .status {
    padding-bottom: 1rem;
  }
}
</style>
