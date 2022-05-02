<template>
  <div id="app">
    <Title />
    <HeroJumbotron />
    
  </div>
</template>

<script>
import Title from './components/Title.vue'
import HeroJumbotron from './components/HeroJumbotron.vue'

export default {
  name: 'App',
  components: {
    Title,
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
  margin-top: 60px;
}
</style>
