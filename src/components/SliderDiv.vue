<template>
  <div class="slider">
    <div class="container">
      <div class="slider__img">
        <img class="slider__img" src="/img/rose.jpg" alt="rose" />
        <img class="slider__img" src="/img/snow.jpg" alt="snow" />
        <img class="slider__img" src="/img/rose.jpg" alt="rose" />
        <img class="slider__img" src="/img/snow.jpg" alt="snow" />
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
  padding: 1rem 3rem;
}
.slider__img {
  display: flex;
  flex-direction: row;
}
.slider__img {
  width: 50%;
  height: 100%;
  object-fit: cover;
}
</style>
