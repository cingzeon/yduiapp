<template>
  <yd-navbar title="NavBar">
    <router-link to="#" slot="left">
      <yd-navbar-back-icon />
    </router-link>
    <router-link to="#" slot="right">
      <yd-navbar-next-icon />
    </router-link>
  </yd-navbar>

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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
