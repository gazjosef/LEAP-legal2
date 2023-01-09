<template>
  <header class="header | u-fs-600 u-fw-bold u-text-white">
    <h1>HEADER</h1>
  </header>
</template>

<script>
export default {
  name: 'LayoutHeader',
}
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  padding: 1.5rem;

  position: fixed;
  left: 50%;
  transform: translateX(-50%);
  top: 0;

  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
