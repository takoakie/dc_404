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
@media screen and (min-width: 781px){
  .header{
    font-family: Inconsolata;
font-size: 24px;
font-style: normal;
font-weight: 700;
line-height: 25px;
letter-spacing: -0.08em;
text-align: left;

color: #333333;
  }
  .button{
    font-family: Space Mono;
font-style: normal;
font-weight: bold;
font-size: 14px;
line-height: 21px;
/* identical to box height */

letter-spacing: -0.035em;
text-transform: uppercase;

background: #333333;

  }
  .img{
    position: absolute;
left: 5.35%;
right: 57.21%;
top: 24.54%;
bottom: 37.11%;

  }
  .footer{
    font-family: Montserrat;
font-size: 14px;
font-style: normal;
font-weight: 600;
line-height: 17px;
letter-spacing: 0em;
text-align: left;

  }
@media screen and (max-width: 780px){
  .header{
position: absolute;
    white-space: nowrap;
    width: 133px;
    height: 25px;
    left: 24px;
    top: 20px;
    font-family: Inconsolata;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 25px;
    letter-spacing: -0.08em;
    text-transform: uppercase;
    color: #333333;
  }
  .button{
    olor: #ffffff;
    size: 14px;
    position: absolute;
    width: 216px;
    height: 68px;
    left: 24px;
    top: 726px;
    background: #333333;
  }
  .img{
    width: 286.83px;
    height: 220.35px;
    top: 109px;
    left: 44px;
    position: absolute;
  }
  .footer{
    position: absolute;
    width: 226px;
    height: 17px;
    left: 75px;
    top: 890px;
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #333333;
  }
  }
  
}

</style>
