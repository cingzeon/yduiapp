<template>
  <div class="home">
    <NavHeaderTabBar />
    <Content></Content>
    <NavFooterTabBar />
  </div>
</template>

<script>
  import NavFooterTabBar from '../../components/NavFooterTabBar'
  import NavHeaderTabBar from '../../components/NavHeaderTabBar'
  import Content from '../../components/Content'
  export default {
    components: {
      NavFooterTabBar,
      NavHeaderTabBar,
      Content
    },
    date(){
      return {
        msg: ``
      }
    }
  }
</script>
