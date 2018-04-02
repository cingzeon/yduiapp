<template>
  <div class="header-tab-bar">
    <yd-navbar title="NavBar">
      <router-link to="#" slot="left">
        <yd-navbar-back-icon />
      </router-link>
      <router-link to="#" slot="right">
        <yd-navbar-next-icon />
      </router-link>
    </yd-navbar>
  </div>
</template>

<script>
  import Vue from 'vue';
  import {NavBar, NavBarBackIcon, NavBarNextIcon} from 'vue-ydui/dist/lib.rem/navbar';


  const Navs = [
    NavBar.name,
    NavBar,
    NavBarBackIcon.name,
    NavBarBackIcon,
    NavBarNextIcon.name,
    NavBarNextIcon
  ];

  Vue.component(Navs);

  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>
