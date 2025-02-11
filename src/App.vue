<template>
  <div id="app">
    <BasicLayout />
  </div>
</template>

<script setup lang="ts">
import BasicLayout from '@/layouts/BasicLayout.vue'
// 在 access.ts 中获取
// import { healthUsingGet } from '@/api/mainController'
// import { useLoginUserStore } from '@/stores/useLoginUserStore'
//
// const loginUserStore = useLoginUserStore()
// loginUserStore.fetchLoginUser()
//
// healthUsingGet().then((res) => {
//   console.log(res)
// })
</script>
