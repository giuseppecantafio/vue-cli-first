<template>
  <div id="app">
    <MainJumbotron/>
    <HelloWorld/>
    <MainTitle/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainTitle from './components/MainTitle.vue'
import MainJumbotron from './components/MainJumbotron.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MainTitle,
    MainJumbotron

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
  margin-top: 60px;
}
</style>
