<template>
  <div class="help">
    <div class="container">
      <h1 class="help_title"> 
        Помощь
      </h1>
    <div class="help_box">
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/building-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">О компании HotSkins</h2><p class="help_item-text">3 статьи</p></div></router-link>
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/link-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">Где найти ссылку на обмен</h2><p class="help_item-text">3 статьи</p></div></router-link>
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/card-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">Пополнение баланса</h2><p class="help_item-text">5 статей</p></div></router-link>
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/key-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">Подключение своего проекта</h2><p class="help_item-text">5 статей</p></div></router-link>
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/sad-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">Проблемы с обменом</h2><p class="help_item-text">5 статей</p></div></router-link>
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/security-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">Как обезопасить себя в сделках</h2><p class="help_item-text">5 статей</p></div></router-link>
      <router-link to=""><div class="help_item"><div class=""><img src="../assets/img/analysis-icon.png" alt=""></div><div class="help_item-textbox"></div><h2 class="help_item-title">Аналитика и отчетность</h2><p class="help_item-text">3 статьи</p></div></router-link>
    </div>
    </div>
  </div>
</template>
<style scoped>

  .container{
    max-width: 1260px;
    width: 100%;
    margin: 0 auto;
    padding: 0 15px;
  }
  .help_title {
    padding-top: 48px;
    padding-bottom: 48px;
    font-size: 48px;
    line-height: 56px;
    font-family: 'rb';
    color: white;
  }
  .help {
height: 848px;
    background-color: #272E3B;
  }
.help_item {
  width: 288px;
  height: 160px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background: #20222A;
box-shadow: 0px 6px 12px -6px rgba(24, 39, 75, 0.12), 0px 8px 24px -4px rgba(24, 39, 75, 0.08);
border-radius: 16px;

}
.help_box {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 24px;
  
}
.help_item img {
  padding-top: 20px;
  padding-left: 16px;
}
.help_item-title {
  font-size: 18px;
  line-height: 24px;
  font-family: 'rm';
  color: white;
  letter-spacing: 0.065rem;
  padding-left: 16px;
  padding-right: 16px;

}
.help_item-text {
  font-family: 'rr';
  font-size: 14px;
  line-height: 20px;
  color: white;
  opacity: 0.5;
  padding-left: 16px;
  padding-bottom: 16px;
}











@media(max-width: 941px) {
  .help {
    height: auto !important;
  }
  .help_box {
    padding-bottom: 60px;
  }
  
}
</style>