<script setup>

</script>

<template>
  <div class="app flex flex-col h-screen">
    <router-view/>

    <van-tabbar class="shrink-0" placeholder>
      <van-tabbar-item icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item icon="search">搜索</van-tabbar-item>
      <van-tabbar-item icon="friends-o">联系</van-tabbar-item>
      <van-tabbar-item icon="setting-o">设置</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<style scoped>

</style>
