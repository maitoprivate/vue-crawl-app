<template>
  <div id="app">
    <Navbar/>
    <Main/>
  </div>
</template>

<script>
import Main from './components/Main.vue'
import Navbar from './components/Navbar.vue'
export default {
  name: 'App',
  components: {
    Main,
    Navbar
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
}
</style>
