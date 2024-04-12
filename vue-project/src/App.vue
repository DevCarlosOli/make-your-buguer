<script>
  import Navbar from './components/Navbar.vue';
  import Footerbar from './components/Footerbar.vue';

  
  export default {
    components: {
      Navbar,
      Footerbar
    }
  }

</script>

<template>    
  <Navbar />
  <RouterView />
  <Footerbar />
</template>

<style scoped>

</style>
