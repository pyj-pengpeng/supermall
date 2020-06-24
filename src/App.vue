<template>
  <div id="app">
    <tab-bar>
      <main-tab-bar></main-tab-bar>
    </tab-bar>
    <router-view></router-view>
  </div>
</template>

<script>
  import TabBar from "./components/common/tabbar/TabBar";
  import MainTabBar from "./components/content/mainTabbar/MainTabBar";
  export default {
    name: 'App',
    components: {
      TabBar,
      MainTabBar
    }
  }
</script>

<style>
  @import "./assets/css/base.css";

</style>
