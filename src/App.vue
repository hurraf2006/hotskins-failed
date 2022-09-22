<template>
  <v-header></v-header>
  <router-view/>
  <v-footer></v-footer>
</template>
<script>
  import vFooter from './components/v-footer.vue';
  import vHeader from './components/v-header.vue';
  export default {
    name: 'app',
    components: {
    vHeader,
    vFooter,
  
}
  }

</script>





<style>
a {
  text-decoration: none;
}
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

</style>
