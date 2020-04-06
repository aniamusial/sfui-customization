<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <SfButton>Hello</SfButton>
  </div>
</template>

<script>
import { SfButton } from "@storefront-ui/vue";

export default {
  name: 'App',
  components: {
    SfButton
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
