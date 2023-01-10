<template>
  <header
    class="header | u-flex u-justify-between | u-fs-600 u-fw-bold u-text-white"
  >
    <UILogo />

    <LayoutNavbar />

    <div class="login">
      <a href="#" class="u-text-white">Login</a>
      <UIButton />
    </div>
  </header>
</template>

<script>
export default {
  name: 'LayoutHeader',
}
</script>

<style lang="scss" scoped>
.header {
  padding: 1.5rem;

  position: fixed;
  left: 50%;
  transform: translateX(-50%);
  top: 0;
}
</style>
