<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <h1>{{ msg }}</h1>

  <img class="stream-box" src="http://172.16.17.237" />
</template>

<style>
body {
  background-color: #1a1a1a;
}
h1 {
  font-size: 1.5rem;
  margin-bottom: 3rem;
  color: #979797;
  text-shadow: #585858;
}
.stream-box {
  width: 640px;
  height: 480px;
  border-radius: 1rem;
  box-shadow: 0 0 2em #41b883;
}
</style>
