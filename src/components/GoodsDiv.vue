<script setup>
import CardDiv from './CardDiv.vue';
</script>
<template>
  <div class="goods">
    <div class="container">
      <h1>Каталог календарей</h1>
      <div class="goods__card">
        <CardDiv />
        <CardDiv />
        <CardDiv />
        <CardDiv />
        <CardDiv />
        <CardDiv />
        <CardDiv />
        <CardDiv />
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  background-color: #b9d635;
  max-width: 90rem;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  padding: 1rem 3rem;
}
.goods__card {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  justify-items: center;
  row-gap: 2rem;
}
</style>
