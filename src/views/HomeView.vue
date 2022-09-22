<template>
<div class="home">
  <div style="height: 848px" class="container">
    <h1 class="home_title">Принимайте платежи
от пользователей
с помощью скинов CS:GO и DOTA 2</h1>

<button>
  Подключить проект
</button>
  </div>
</div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
 
  }
}
</script>
<style scoped>
 .container {
max-width: 1224px;
width: 100%;
margin: 0 auto;
padding: 0 15px;
}
  button {
    font-family: 'rb';
    font-size: 16px;
    line-height: 20px;
    color: #20222A;
    background-color: #F4C038;
    padding: 22px 40px;
    border-radius: 48px; 
    
  }
 
  .home_title {
    padding-top: 111px;
    margin-bottom: 40px;
    font-size: 56px;
    line-height: 60px;
    font-family: 'rb';
    color: white;
    width: 624px;
  }
.home{
  width: 100%;
  height: 100%;
  background-image: url(../assets/img/homebg.png);
  background-position: center;
  background-size: cover;
}
</style>