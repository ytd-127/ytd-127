<template>
  <div id="app">
    <main-nav></main-nav>
    
    <router-view/>

    <bottom></bottom>
    
  </div>
</template>

<script>

import MainNav from "components/content/mainNav/MainNav"
import Bottom from "components/content/bottom/Bottom"



export default {
  name: 'App',
  components: {
    MainNav,
    Bottom
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
