<template>
  <div id="app">
    <img alt="./assets/favicon.png" src="./assets/Scarecrow.png">
    <HelloWorld msg="I have bad news for you"/>
  </div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Space Mono;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
