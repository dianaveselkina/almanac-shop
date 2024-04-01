<script setup>
defineProps({
  imageUrl: String,
  price: Number,
  isFavorite: Boolean,
  isAdded: Boolean,
});
</script>
<template>
  <div class="card">
    <div class="card__like">
      <img
        class="card__icon"
        :src="isFavorite ? '/img/like_icon.png' : '/img/like1_icon.png'"
        alt="basket_icon"
      />
    </div>
    <div class="card__image">
      <img class="card__img" :src="imageUrl" alt="rose" />
    </div>
    <div class="card__price">
      <p>{{ price }}</p>
      <img
        class="card__icon"
        :src="isAdded ? '/img/basket_icon.png' : '/img/basket1_icon.png'"
        alt="basket_icon"
      />
    </div>
  </div>
</template>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: clamp(18rem, 20%, 20rem);
  height: 24rem;
  border: solid 3px #63625d;
  border-radius: 1rem;
  padding: 1rem 1.5rem;
  gap: 1rem;
}
.card:hover {
  cursor: pointer;
  box-shadow: 0px 0px 13px 4px #63625d;
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
