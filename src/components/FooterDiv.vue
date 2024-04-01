<template>
  <div class="footer">
    <div class="container">
      <div class="footer__wrapper">
        <div class="footer__logo">
          <img src="/img/logo.png" alt="logo" />
          <h1 class="header__title">almanac-shop</h1>
        </div>
        <div class="footer__developers-item">
          Developer:
          <a
            class="footer__developers-link"
            href="https://t.me/DianaVeselkina"
            target="_blank"
            rel="noopener"
            >Diana Veselkina</a
          >
        </div>
      </div>
      <div class="footer__copyright">
        <hr />
        <p class="footer__copyright">© almanac shop, 2024</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  background-color: #b9d635;
  max-width: 90rem;
  margin: 0 auto;
  padding: 1rem 3rem;
}
.footer__wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.footer__logo {
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
  font-size: 1rem;
  text-transform: uppercase;
  color: #63625d;
}
</style>
