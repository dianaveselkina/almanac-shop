<template>
  <div class="card">
    <div class="card__like">
      <img class="card__icon" src="/img/like_icon.png" alt="like_icon" />
    </div>
    <div class="card__image">
      <img class="card__img" src="/img/rose.jpg" alt="rose" />
    </div>
    <div class="card__price">
      <p>200р</p>
      <img class="card__icon" src="/img/basket_icon.png" alt="basket_icon" />
    </div>
  </div>
</template>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: clamp(7rem, 20%, 20rem);
  height: 18rem;
  border: solid 1px #63625d;
  border-radius: 1rem;
  padding: 1rem 1.5rem;
  gap: 1rem;
}
.card__like {
  display: flex;
  justify-content: flex-end;
}
.card__icon {
  width: 1.5rem;
  height: 1.5rem;
}
.card__image {
  display: flex;
  justify-content: center;
}
.card__img {
  border-radius: 1rem;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.card__price {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
</style>
