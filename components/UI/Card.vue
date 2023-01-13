<template>
  <div class="card">
    <img
      class="card__img"
      :src="require(`@/assets/images/${image}.jpg`)"
      :alt="title"
    />
    <div class="card__text">
      <h2
        class="heading-secondary-100 | u-margin-bottom-small u-text-primary-200"
      >
        {{ title }}
      </h2>
      <p class="paragraph">
        {{ excerpt }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    box: String,
    image: String,
    title: String,
    excerpt: String,
  },
  name: 'UiCard',
}
</script>

<style lang="scss" scoped>
.card {
  box-shadow: 0 1.5rem 4rem rgba(#000, 0.15);
  border-radius: 5px;
  height: 32rem;
  max-width: 32rem;

  // @include respond(desktop) {
  //   width: 32.2rem;
  // }

  &__img {
    border-radius: 5px 5px 0 0;
    height: 16rem;
    width: 100%;
    object-fit: cover;
  }

  &__text {
    padding: 2.5rem 2.25rem;

    p {
      line-height: 1.4;
    }
  }
}
</style>
