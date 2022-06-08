<template>
  <div id="app">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
    <header_icon msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import header_icon from './components/header_icon.vue'

export default {
  name: 'App',
  components: {
    header_icon
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
