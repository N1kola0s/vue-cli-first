<template>
  <div id="app">
    <HelloWorld />
    <HeroJumbotron />
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeroJumbotron from './components/HeroJumbotron.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    HeroJumbotron


  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
