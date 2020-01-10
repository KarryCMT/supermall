<template>
  <div id="app">
    <MainTabBar></MainTabBar>
    <router-view/>
  </div>
</template>
<script>
import MainTabBar from 'components/content/mainTabbar/MainTabBar'
export default {
  name:'app',
  components:{
    MainTabBar,
  }
}
</script>
<style lang="less">
@import '/assets/css/normalize.css';
@import '/assets/css/base.css';
</style>
