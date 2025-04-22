<script setup>

</script>

<template>
  <div class="view home-view">
    <van-nav-bar class="placeholder" fixed placeholder title="标题" />

    <div class="view__main home-view__main">
      <van-cell-group v-for="v in 100" :title="`分组${v}`">
        <van-cell title="单元格" value="内容" />
      </van-cell-group>
    </div>
  </div>
</template>

<style scoped>

</style>
