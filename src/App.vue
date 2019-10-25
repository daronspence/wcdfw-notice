<template>
  <div id="app">
    <img alt="WC DFW Logo" src="https://i0.wp.com/wpdfw.org/wp-content/uploads/2016/10/cropped-wordcamp-logo-2-color-web.png?fit=240%2C159&ssl=1">
    <Welcome />
  </div>
</template>

<script>
import Welcome from './components/Welcome.vue'

export default {
  name: 'app',
  components: {
    Welcome
  }
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
