<template>
  <!-- 这个div是根容器 -->
  <div id="app">
    <!-- 这里会显示当前路由对应的组件 -->
    <router-view />
  </div>
</template>

<script setup>

</script>

<style>
/*全局样式*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
  line-height: 1.6;
}

/* #app {
  min-height: 100vh; 
} */
</style>