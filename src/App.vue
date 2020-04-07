<template>
  <div id="app">
    <MyCoolBanner title="Hello"></MyCoolBanner>
  </div>
</template>

<script>
import MyCoolBanner from "./components/MyCoolBanner"

export default {
  name: 'App',
  components: {
    MyCoolBanner
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
