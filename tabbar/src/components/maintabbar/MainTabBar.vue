<template>
 <tab-bar>
   <tab-bar-item path="/home" activeColor="deeppink">
     <img slot="item-icon" src="~assets/img/tabbar/home.png" />
     <img slot="item-icon-active" src="~assets/img/tabbar/home-active.png" />
     <div slot="item-text">首页</div>
   </tab-bar-item>
   <tab-bar-item path="/category" activeColor="deeppink">
     <img slot="item-icon" src="~assets/img/tabbar/Category.png" />
     <img slot="item-icon-active" src="~assets/img/tabbar/Category-active.png" />
     <div slot="item-text">分类</div>
   </tab-bar-item>
   <tab-bar-item path="/cart" activeColor="deeppink">
     <img slot="item-icon" src="~assets/img/tabbar/cart.png" />
     <img slot="item-icon-active" src="~assets/img/tabbar/cart-active.png" />
     <div slot="item-text">购物车</div>
   </tab-bar-item>
   <tab-bar-item path="/profile" activeColor="deeppink">
     <img slot="item-icon" src="~assets/img/tabbar/me.png" />
     <img slot="item-icon-active" src="~assets/img/tabbar/me-active.png" />
     <div slot="item-text">我的</div>
   </tab-bar-item>
 </tab-bar>
</template>

<script>
  import TabBar from 'components/tabbar/TabBar.vue'
  import TabBarItem from 'components/tabbar/TabBarItem.vue'
  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>
</style>
