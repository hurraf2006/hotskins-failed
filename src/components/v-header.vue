<template>
<nav>
  <div style="display: flex; align-items: center; justify-content: space-between;"  class="container">
  <div class="v-header-grouplinks"> 
    
    <router-link class="router-link_logo router_link" to="/"><img src="../assets/img/logo.png" alt=""><h2><span>Hot</span>Skins</h2></router-link> 
   
    <router-link class="router_link rt1 mrt1" to="/help">Помощь</router-link>
    <router-link class="router_link mrt2" to="/contacts">Контакты</router-link>

   </div>
   <div class="v-header-grouplinks2">
     <select name="" id="">
       <option value="">RU</option>
       <option value="">EN</option>
     </select>
    <router-link class="login_btn">Войти</router-link>
   </div>
  </div>
  
</nav>
</template>

<script>
export default {
  name: 'v-header',
  props: {
  
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @font-face {
    font-family: 'rb';
    src: url(../assets/fonts/Rubik-Bold.ttf);
}

@font-face {
    font-family: 'rm';
    src: url(../assets/fonts/Rubik-Medium.ttf);
}

@font-face {
    font-family: 'rr';
    src: url(../assets/fonts/Rubik-Regular.ttf);
}
  .router_link {
    font-family: 'rm';
    font-size: 14px;
    line-height: 16px;
    color: white;
    letter-spacing: 0.07rem;
    
  }
  .rt1 {
    margin-right: 32px;
  }
  .router-link_logo{
    display: flex;
    margin-right: 140px;
    align-items: center;
    gap: 14px;
  }
  .router-link_logo h2 {
    font-family: 'rr';
    font-size: 18px;
    line-height: 22px;
    
  }
  .router-link_logo span {
    font-family: 'rb' !important;
    font-size: 22px;
  }
  .v-header-grouplinks {
    display: flex;
justify-content: space-between;
align-items: center;
  }

.container {
max-width: 1224px;
width: 100%;
margin: 0 auto;
padding: 0 15px;
}
nav {
  background-color: #20222A;
  padding: 16px 0;
}
.router_link.router-link-exact-active {
  color: #F4C038;
}

.login_btn {
  font-size: 16px;
  line-height: 20px;
  font-family: 'rm';
  color: #20222A;
}

</style>
