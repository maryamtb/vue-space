<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">

    <reverseString  :message="'egassem desrever a si siht'" />
    <reverseString  :message="'a different message to reverse'" />

  </div>
</template>

<script>
import reverseString from '@mimooo/vue-reverse-str-button'

export default {
  name: 'App',
  components: {
    reverseString
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
