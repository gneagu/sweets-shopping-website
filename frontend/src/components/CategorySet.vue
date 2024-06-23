<template>
  <div>
    <!-- <h1 class="categorySetTitle">Categories</h1> -->
    <div class="categorySet">
      <RouterLink to="/prajituri"><CategoryTile title-text="Prajituri" image-source="..assets\1.jpeg"/></RouterLink> 
      <RouterLink to="/fursecuri"><CategoryTile title-text="Fursecuri" image-source="2.jpeg"/></RouterLink> 
      <RouterLink to="/torturi"><CategoryTile title-text="Torturi" image-source="3.jpg"/></RouterLink> 
      <RouterLink to="/macaroons"><CategoryTile title-text="Macaroons" image-source="4.jpeg"/></RouterLink> 
    </div>
  </div>
</template>

<script setup lang="ts">
import CategoryTile from './CategoryTile.vue'

</script>

<style scoped>
.categorySet {
  display: flex;
  width: 100%;
  grid-template-columns: repeat(4, 1fr);
  /* grid-template-columns: fit-content(40%); */
  justify-content: space-between;
  /* padding: 10px 0; */
  grid-gap: 1rem;
}

.categorySetTitle {
  color: #333;
  font-weight: bold;
  padding: 10px 0;
  font-size: 24px;
}
</style>
