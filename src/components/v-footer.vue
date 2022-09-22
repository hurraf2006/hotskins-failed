<template>
    <footer>
        <div class="container footer_box">
            <p class="copy_text">Copyright © Skincash.ru</p>
            <div class="footer_nav">
                <router-link class="router_link flink rt1" to="/help">Помощь</router-link>
    <router-link class="router_link flink" to="/contacts">Контакты</router-link>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        name: 'v-footer'
    }
</script>
<style>
    .container {
        max-width: 1224px;
        width: 100%;
        margin: 0 auto;
        padding: 0 15px;

    }
    footer {
        background-color: #20222A;
    }
    .footer_box {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 48px;
    }
    .copy_text, .flink {
        font-family: 'rr';
        font-size: 14px;
        line-height: 20px;
        color: white;
        opacity: 50%;
    }
    
   
    .router_link.router-link-exact-active {
  color: #F4C038;
}
.footer_nav {
    display: flex;
    gap: 32px;
}

</style>