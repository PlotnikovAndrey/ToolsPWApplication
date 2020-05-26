<template>
  <div id="app">
    <div class="scroll"> 
    <img class="image" src="images/image 11.png"> 
    <img class="image1" src="images/image 12.png">
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
body {
  background-image: url('./assets/3(2).png'); 
}
::-webkit-scrollbar {
    width: 12px;
}
::-webkit-scrollbar-button {background: rgba(0,0,0,0)
}
::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0); 
    border-radius: 10px;
}
 
::-webkit-scrollbar-thumb {
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,2); 
}
.scroll {
height: 321px;
width: 310px;
background: #fff;
border: 1px solid #C1C1C1;
overflow-y: scroll;
position: relative;
top: 239px;
left: 5px;
opacity: .9;
border: 1px solid transparent;
border-radius: 14px;
}
.image {
position: relative;
top: 20px;
left: 15px;
}
.image1 {
position: relative;
top: 34px;
left: 15px;
}
</style>
