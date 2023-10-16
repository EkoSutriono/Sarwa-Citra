<template>
  <div>
    <div class="header">
      <NavBar />
      <NavMenu />
    </div>
    <Content />
  </div>
</template>

<script>

export default {
  name: 'IndexPage',
}
</script>

<style>

body {
  margin: 0;
}
.header {
  position: fixed;
  top: 0;
  width: 100%;
}
</style>