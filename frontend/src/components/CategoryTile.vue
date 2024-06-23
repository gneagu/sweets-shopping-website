<template>
  <div class="tile">
    <div class="image">
      <img :src="'../assets/' + imageSource + ''" alt="alternatetext" />
    </div>
    <div class="title">
      <h1>{{titleText}}</h1>
    </div>
  </div>
</template>

<script setup lang="ts">
const props = defineProps(['titleText', 'imageSource'])

image:

console.log(props.titleText)
console.log(props.imageSource)
</script>

<style scoped>
.tile {
  max-width: 100%;
  padding: 0;
}

.image {
  max-width: 100%;
  padding: 0;
}

.title {
  color: #333;
  font-weight: bold;
  padding: 10px 0;
}
</style>
