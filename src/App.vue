<template>
  <div id="app">
    <NavBar />
    <alert type="success/info/danger/warning">...</alert>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import {alert} from 'vue-strap'

export default {
  name: 'app',
  components: {
    NavBar,
    alert,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
}
</style>
