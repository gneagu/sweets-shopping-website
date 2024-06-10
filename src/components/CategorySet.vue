<template>
  <div>
    <h1 class="categorySetTitle">Set Title</h1>
    <div class="categorySet">
      <CategoryTile />
      <CategoryTile />
      <CategoryTile />
      <CategoryTile />
    </div>
  </div>
</template>

<script setup lang="ts">
import CategoryTile from './CategoryTile.vue'
</script>

<style scoped>
.categorySet {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 1rem;
}

.categorySetTitle {
  color: #333;
  font-weight: bold;
  padding: 10px 0;
  font-size: 24px;
}
</style>
