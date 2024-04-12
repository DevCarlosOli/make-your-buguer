<script>
  import Navbar from './components/Navbar.vue';
  import Footerbar from './components/Footerbar.vue';

  
  export default {
    components: {
      Navbar,
      Footerbar
    },
    data(){
      return{
        logo_src: "/img/logo.png",
        app_name: "Make Your Burguer"
      }
    }
  }

</script>

<template>    
  <Navbar :logo="logo_src" :alt="app_name" />
  <RouterView />
  <Footerbar />
</template>

<style>
  *{
    font-family: Helveltica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  .main-container{
    margin: 50px;
    min-height: 250px;
  }

  h1{
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>
