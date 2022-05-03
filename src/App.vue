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
  margin-top: 60px;
}
h1{
  background: -webkit-linear-gradient(rgb(222, 91, 91), rgb(109, 26, 30));
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
