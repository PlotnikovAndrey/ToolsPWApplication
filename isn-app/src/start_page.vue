<template>
  <div id="app">
     <button class="btn btn-default">Бронирование<br>номера</button>
     <button class="btn1 btn-default1">Фотографии</button>
     <br><br>
     <button class="btn2 btn-default2">Ресторан отеля</button>
     <button class="btn3 btn-default3">О нас</button>
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
  background-image: url('./assets/1.png');
}
.btn {
    display: inline-block;
    padding: 0.2em 0.5em;
    font-size: 1.12em;
    font-weight: 600;
    line-height: 1;
    text-align: center;
    border: 2px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: 24.8em;
    left: 0.8em;
}

.btn1 {
    display: inline-block;
    padding: 0.19em 0.9em;
    font-size: 1.12em;
    font-weight: 600;
    line-height: 2;
    text-align: center;
    border: 2px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: 25.25em;
    left: 1.64em;
}

.btn2 {
    display: inline-block;
    padding: 0.16em 0.33em;
    font-size: 1.12em;
    font-weight: 600;
    line-height: 2;
    text-align: center;
    border: 2px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: 24.5em;
    left: 0.8em;
}

.btn3 {
    display: inline-block;
    padding: 0.27em 2.6em;
    font-size: 1.08em;
    font-weight: 600;
    line-height: 2;
    text-align: center;
    border: 2px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: 25.38em;
    left: 1.7em;
}

.btn-default {
    color: red;
    background-color: #fff;
    border-color: red;

}

.btn-default1 {
    color: blue;
    background-color: #fff;
    border-color: blue;

}

.btn-default2 {
    color: orange;
    background-color: #fff;
    border-color: orange;

}

.btn-default3 {
    color: green;
    background-color: #fff;
    border-color: green;

}
</style>