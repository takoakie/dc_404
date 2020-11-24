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
  },
};
</script>

<style>
@media screen and (min-width: 781px){
  .header{
    color: #333333;
    white-space: nowrap;
    position: absolute;
    width: 133px;
    height: 25px;
    left: 77px;
    top: 40px;
    font-family: "Inconsolata";
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 25px;
    letter-spacing: -0.08em;
    text-transform: uppercase;
  }
  .button{
    color: #ffffff;
    size: 14px;
    position: absolute;
    width: 216px;
    height: 68px;
    left: 740px;
    top: 663px;
    background: #333333;
  }
  .img{
     width: 539.22px;
    height: 414.25px;
    top: 265px;
    left: 77px;
    position: absolute;
  }
  .footer{
   position: absolute;
    width: 226px;
    height: 17px;
    left: 607px;
    top: 1024px;
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #333333;

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
    color: #ffffff;
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
