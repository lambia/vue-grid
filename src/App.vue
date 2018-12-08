<template>
  <div id="app">
    <Base />
  </div>
</template>

<script>
import Base from './components/Base.vue'

export default {
  name: 'app',
  components: {
    Base
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
