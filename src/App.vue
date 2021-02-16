<template>
  <img alt="Vue logo" :src="img" />
  <div class="img"></div>
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import img from "@/assets/logo.png";
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.img {
  width: 200px;
  height: 200px;
  background: url("@/assets/logo.png") center / contain no-repeat;
}
</style>
