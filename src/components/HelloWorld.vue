<template>
<div>
  <p class="badnews">{{ msg }}</p>
      <div>
      <p class= "message">
      the page you are looking for might be removed or is temporarily unavailable
     </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
@media screen and(min-width: 781px){
.badnews {
  position: absolute;
  width: 586px;
  height: 190px;
  left: 735px;
  top:265px;
  font-family: Space Mono;
  font-style: normal;
  font-weight: bold;
  font-size: 64px;
  line-height: 95px;
  letter-spacing: -0.035em;
}
.message {
  position: absolute;
width: 381px;
height: 108px;
left: 736px;
top: 491px;

font-family: Space Mono;
font-style: normal;
font-weight: normal;
font-size: 24px;
line-height: 36px;
letter-spacing: -0.035em;

color: #4F4F4F;
}
@media screen and(max-width:780px){
  .badnews
  {position: absolute;
    width: 350px;
    height: 142px;
    left: 24px;
    top: 407px;
    font-family: "Space Mono";
    font-style: normal;
    font-weight: bold;
    font-size: 48px;
    line-height: 71px;
    letter-spacing: -0.035em;
    color: #333333;
  }
} .message {
    position: absolute;
    width: 328px;
    height: 81px;
    left: 23px;
    top: 578px;
    font-family: "Space Mono";
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    letter-spacing: -0.035em;
    color: #4F4F4F;
  }

}
</style>
}