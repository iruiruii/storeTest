<template>

  <Index />
  <Tabbar>
    <TabbarItem>
      <template v-slot:tabbar-img><img src='./assets/img/home_unpress.png' /></template>
      <template v-slot:tabbar-img-active><img src='./assets/img/home_pressed.png' /></template>
      <template v-slot:tabbar-text>首页</template>
    </TabbarItem>
    <TabbarItem>
      <template v-slot:tabbar-img><img src='./assets/img/store_unpress.png' /></template>
      <template v-slot:tabbar-img-active><img src='./assets/img/store_pressed.png' /></template>
      <template v-slot:tabbar-text>首页</template>
    </TabbarItem>
    <TabbarItem>
      <template v-slot:tabbar-img><img src='./assets/img/cart_unpress.png' /></template>
      <template v-slot:tabbar-img-active><img src='./assets/img/cart_pressed.png' /></template>
      <template v-slot:tabbar-text>首页</template>
    </TabbarItem>
    <TabbarItem>
      <template v-slot:tabbar-img><img src='./assets/img/my_unpress.png' /></template>
      <template v-slot:tabbar-img-active><img src='./assets/img/my_pressed.png' /></template>
      <template v-slot:tabbar-text>首页</template>
    </TabbarItem>
  </Tabbar>
  
</template>

<script>

  import Index from './components/Index.vue';
  import Tabbar from './components/common/Tabbar/Tabbar.vue';
  import TabbarItem from './components/common/Tabbar/TabbarItem.vue'

  export default {
    name: 'App',
    components: {
      Index, Tabbar, TabbarItem
    }
  }
</script>

<style>
  @import './assets/css/base.css';
</style>
