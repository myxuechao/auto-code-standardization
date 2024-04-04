<!--
 * @Author: LiuXueChao
 * @Date: 2024-04-03 16:35:55
 * @LastEditors: your name
 * @LastEditTime: 2024-04-05 02:57:50
 * @Description: file content
-->
<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
console.log("在App.vue中增加czg的测试");
console.log("xxxxxx");
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  transition: filter 300ms;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
