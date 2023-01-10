<template>
  <button type="button" class="button | u-bg-primary-300 u-text-white">
    Create Free Account
  </button>
</template>

<script>
export default {
  name: 'UiButton',
}
</script>

<style lang="scss" scoped>
.button {
  border-radius: 6px;
  border: none;
  height: 4rem;
  width: 18rem;
  z-index: 10;

  &:hover {
    // background-color: $clr-primary-100;
    transform: scale(1, 0.9);

    .prevText {
      display: none;
    }

    .newText {
      display: block;
    }
  }
}
</style>
