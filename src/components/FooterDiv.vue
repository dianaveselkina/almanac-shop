<template>
  <div class="footer">
    <div class="container">
      <div class="footer__logo">
        <img src="/img/logo.png" alt="logo" />
        <h1 class="header__title">almanac-shop</h1>
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
.header__logo {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 1rem;
}
img {
  width: 8rem;
  height: 8rem;
}
.header__title {
  font-size: 2rem;
  text-transform: uppercase;
  color: #63625d;
}
.header__img {
  width: 2rem;
  height: 2rem;
}
</style>
