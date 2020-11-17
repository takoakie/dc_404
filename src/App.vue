<template>
<div>
  <header class = "header"> {{ header }} </header>
  <div id="img">
    <img class="img" alt="Scarecrow" src="./assets/Scarecrow.png"/>
    </div>
    <HelloWorld msg="I have bad news for you"/>
     <button class="button"> BACK TO HOMEPAGE </button>

     <footer class ="footer">{{ fotter }}</footer>
     </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default{
  data: function(){
  return{
    header: "404 NOT FOUND",
    footer:"Your name @ DevChallenge.io"
  };
},
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
