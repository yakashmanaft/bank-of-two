<template>
  <Header />
  <main-dashboard msg="Welcome to Your Vue.js App" />
</template>

<script>
import Header from './components/Header.vue'
import MainDashboard from './components/MainDashboard.vue'

export default {
  name: 'App',
  components: {
    Header,
    MainDashboard
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
