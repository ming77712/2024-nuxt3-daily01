<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>
    Page: 首頁
    <p>目前路由的路徑 - route.fullPath 為: {{ route.fullPath }}</p>
  </div>
</template>

<style scoped></style>
