<template>
  <div id="app">
    <router-view></router-view>
    <tab-bar>
      <tab-bar-item path="/home">
        <img slot="item-img" src="~assets/img/tabbar/home.png" alt="">
        <img slot="item-img-active" src="~assets/img/tabbar/home-active.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <img slot="item-img" src="~assets/img/tabbar/category.png" alt="">
        <img slot="item-img-active" src="~assets/img/tabbar/categroy-active.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <img slot="item-img" src="~assets/img/tabbar/car.png" alt="">
        <img slot="item-img-active" src="~assets/img/tabbar/car-active.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <img slot="item-img" src="~assets/img/tabbar/profile.png" alt="">
        <img slot="item-img-active" src="~assets/img/tabbar/profile-active.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>

  import TabBar from 'components/common/tabbar/Tabbar'
  import TabBarItem from 'components/common/tabbar/TabbarItem'
  export default {
    name: 'app',
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style>

</style>