<script setup>

</script>

<template>
  <div class="home-view flex flex-col overflow-y-hidden">
    <van-nav-bar class="shrink-0" fixed placeholder title="标题" />

    <div class="home-view__main overflow-y-auto">
      <van-cell-group v-for="v in 100" :title="`分组${v}`">
        <van-cell title="单元格" value="内容" />
      </van-cell-group>
    </div>
  </div>
</template>

<style scoped>

</style>
