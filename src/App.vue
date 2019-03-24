<template>
  <div id="app">
    <airpods></airpods>
  </div>
</template>

<script>
import Airpods from './components/Airpods'

export default {
  name: 'app',
  components: {
    Airpods
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
