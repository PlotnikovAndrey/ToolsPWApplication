<template>
  <div id="app">
    <div class="scroll"> 
    <img class="image" src="images/image 13.png"> 
    <button class="btn5 btn-default5" type="button">Выбрать<br>2500руб./день<br>Номер свободен!</button>
    <button class="btn6 btn-default6" type="button">Узнать подробнее</button>
    <button class="btn7 btn-default7" type="button">Предыдущий номер</button>
    <button class="btn8 btn-default8" type="button">Следующий номер</button> 
    <button class="btn9 btn-default9" type="button">Отправить запрос</button> 
    <form>
      <input class="textfield" placeholder="   Имя" type="text" id="fname" name="fname">
      <input class="textfield" placeholder="   Фамилия" type="text" id="lname" name="lname">
      <input class="textfield" placeholder="   Номер телефона" type="text" id="number" name="number">
    </form>  
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
  background-image: url('./assets/6.png'); 
}

input[type=text] {
  width: 90%;
  padding: 15px 0px;
  margin: 5px 0;
  box-sizing: border-box;
  position: relative;
  top: -70px;
  left: 15px;
  border-radius: 9px;
}

.textfield {
  background-color: Lavender; /* Цвет фона */
  color: black; /* Цвет текста */
}

.scroll {
height: 530px;
width: 310px;
background: #fff;
border: 1px solid #C1C1C1;
position: relative;
top: 32px;
left: 5px;
opacity: .9;
border: 1px solid transparent;
border-radius: 14px;
}
.image {
position: relative;
top: 20px;
left: 11px;
}

.btn5 {
    display: inline-block;
    padding: 6px 10px;
    font-size: 18px;
    font-weight: 600;
    line-height: 0.95;
    text-align: center;
    border: 1px solid transparent;
    border-radius: 1px;
    position: relative; 
    top: -180px;
    left: 19px;
}

.btn-default5 {
    color: orange;
    text-align:left;
    background-color: gray;
    border-color: #ccc;

}

.btn6 {
    display: inline-block;
    padding: 6px 10px;
    font-size: 18px;
    font-weight: 600;
    line-height: 0.95;
    text-align: center;
    border: 1px solid transparent;
    border-radius: 1px;
    position: relative; 
    top: -93px;
    left: 123px;
}

.btn-default6 {
    color: orange;
    text-align:left;
    background-color: gray;
    border-color: #ccc;

}

.btn7 {
    display: inline-block;
    padding: 6px 7px;  
    font-size: 12px;
    font-weight: 600;
    line-height: 0.95;
    text-align: center;
    border: 1px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: -32px;
    left: -150px;
}

.btn-default7 {
    color: white;
    background-color: black;
    border-color: #ccc;

}

.btn8 {
    display: inline-block;
    padding: 6px 11px;
    font-size: 12px;
    font-weight: 600;
    line-height: 0.95;
    text-align: center;
    border: 1px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: -58px;
    left: 168px;
}

.btn-default8 {
    color: white;
    background-color: black;
    border-color: #ccc;

}
.btn9 {
    display: inline-block;
    padding: 8px 65px;
    font-size: 18px;
    font-weight: 600;
    line-height: 0.95;
    text-align: center;
    border: 1px solid transparent;
    border-radius: 9px;
    position: relative; 
    top: 160px;
    left: 13px;
}

.btn-default9 {
    color: white;
    background-color: black;
    border-color: #ccc;

}
</style>