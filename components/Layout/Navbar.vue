<template>
  <ul>
    <li>For People</li>
    <li>For Businesses</li>
    <li>Contact</li>
  </ul>
</template>

<script>
export default {
  name: 'LayoutNavbar',
}
</script>

<style lang="scss" scoped>
ul {
  display: flex;
  align-items: center;
  flex-direction: row;

  li {
    margin-left: 0.75rem;
    margin-right: 0.75rem;
    list-style: none;
  }
}
</style>
