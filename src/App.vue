<script setup>

</script>

<template>
  <div class="app">
    <router-view/>

    <van-tabbar class="placeholder" placeholder>
      <van-tabbar-item icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item icon="search">搜索</van-tabbar-item>
      <van-tabbar-item icon="friends-o">联系</van-tabbar-item>
      <van-tabbar-item icon="setting-o">设置</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<style scoped>
@import "tailwindcss";

.app {
  @apply flex flex-col h-screen;
}
</style>
