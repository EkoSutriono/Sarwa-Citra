<template>
  <div>
    <SpeedInsights/>
    <div class="header">
      <NavBar />
      <NavMenu />
    </div>
    <Content />
  </div>
</template>

<script>
import { SpeedInsights } from "@vercel/speed-insights/vue"

export default {
  name: 'IndexPage',
  components: {
    SpeedInsights,
  }
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