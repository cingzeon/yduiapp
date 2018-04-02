<template>
  <footer class="footer-tab-bar">
    <yd-tabbar>
      <yd-tabbar-item title="首页" link="#">
        <yd-icon name="home-outline" slot="icon" size="0.54rem"></yd-icon>
      </yd-tabbar-item>
      <yd-tabbar-item title="购物车" link="#" dot>
        <yd-icon name="shopcart-outline" slot="icon" size="0.54rem"></yd-icon>
      </yd-tabbar-item>
      <yd-tabbar-item title="个人中心" link="#" active>
        <yd-icon name="ucenter" slot="icon" size="0.54rem"></yd-icon>
        <yd-badge slot="badge" type="danger">2</yd-badge>
      </yd-tabbar-item>
    </yd-tabbar>
  </footer>
</template>

<script type="text/babel">
  import Vue from 'vue';
  import {TabBar, TabBarItem} from 'vue-ydui/dist/lib.rem/tabbar';

  import './index.scss'
  const TabBars = [
    TabBar.name, TabBar,
    TabBarItem.name, TabBarItem
  ];

  Vue.component(TabBars);



  export default {
    data () {
      return {
        msg: ``
      }
    }
  }
</script>








