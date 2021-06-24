<template>

  <Index />
  <Tabbar />
  
</template>

<script>

  import Index from './components/Index.vue';
  import Tabbar from './components/common/Tabbar/Tabbar.vue';

  export default {
    name: 'App',
    components: {
      Index, Tabbar
    }
  }
</script>

<style>
  @import './assets/css/base.css';
</style>
