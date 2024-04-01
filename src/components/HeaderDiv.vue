<template>
  <div class="header">
    <div class="container">
      <img src="/img/logo.png" alt="logo" />
      <input />
      <div class="header__icon">
        <img class="header__img" src="/img/like_icon.png" alt="like_icon" />
        <img class="header__img" src="/img/basket_icon.png" alt="basket_icon" />
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
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 3rem;
}
img {
  width: 8rem;
  height: 8rem;
}
.header__img {
  width: 2rem;
  height: 2rem;
}
input {
  width: 40rem;
  padding: 1rem;
  border-radius: 0.5rem;
}
.header__icon {
  display: flex;
  gap: 3rem;
}
</style>
