<script setup>
import LayoutNav from './components/LayoutNav.vue'
import LayoutHeader from './components/LayoutHeader.vue'
import LayoutFooter from './components/LayoutFooter.vue'
</script>

<template>
  <div class="main">
    <LayoutNav />
    <LayoutHeader />
    <RouterView />
    <LayoutFooter />
  </div>
</template>

<style scoped lang="scss">
.main {
  display: flex;
  flex-direction: column; /* 设置主轴方向为垂直，即上下排列 */
}
</style>
