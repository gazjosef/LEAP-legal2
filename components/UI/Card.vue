<template>
  <div class="feature-box box-1">
    <img
      class="feature-box__img"
      src="@/assets/images/lc-greater-collab@2x.jpg"
      alt="Greater Collaboration"
    />
    <div class="feature-box__text">
      <h2
        class="heading-secondary-100 | u-margin-bottom-small u-text-primary-200"
      >
        Greater Collaboration
      </h2>
      <p class="paragraph">
        Collaborate on documents with clients, lawyers and other parties with
        LawConnect’s Comment and Reply.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  // props: {
  //   image: String,
  //   title: String,
  //   excerpt: String,
  // },
  name: 'UiCard',
}
</script>

<style lang="scss" scoped>
.feature-box {
  box-shadow: 0 1.5rem 4rem rgba(black, 0.15);
  border-radius: 5px;
  height: 32rem;
  width: 100%;

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
