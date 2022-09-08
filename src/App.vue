<template>
  <home-page msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    'home-page': HomePage,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: white;
  /*margin-top: 60px;*/
}

body {
  background: #080808
}
</style>
