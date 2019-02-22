<template>
  <div id="app">
    <NavBar />
    <Locations />
    <Reviews />
    <alert type="success/info/danger/warning">...</alert>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Locations from './components/Locations.vue'
import Reviews from './components/Reviews.vue'
import {alert} from 'vue-strap'

export default {
  name: 'app',
  components: {
    NavBar,
    Locations,
    Reviews,
    alert,
  }
}
</script>

<style>
:root{
    --main-text: #ff1;
    --elite-bgColor: #08021b;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
}
</style>
