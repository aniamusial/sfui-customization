<template>
  <div id="app">
    <MyCoolPlayground></MyCoolPlayground>
  </div>
</template>

<script>
import MyCoolPlayground from "./components/MyCoolPlayground"

export default {
  name: 'App',
  components: {
    MyCoolPlayground
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
