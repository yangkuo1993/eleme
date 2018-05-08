<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import '@/assets/css/reset.css'
export default {
  name: 'App'
}
</script>

<style>
  html,body,#app{
    width: 100%;
    height: 100%;
    font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
  }
</style>
