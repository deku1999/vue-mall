<template>
  <div id="app">
    <keep-alive exclude="Detail">
    <router-view></router-view>
    </keep-alive>
    <TabBar/>
  </div>
</template>

<script>
import TabBar from "components/common/tabbar/TabBar"
export default {
  name: 'App',
  components: {
    TabBar
  }
}
</script>

<style>
  @import url("./assets/css/base.css");
</style>
