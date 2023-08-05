<script setup>
import { ref } from "vue";
const count = ref(0);

const add = () => {
  count.value++;
};

const sub = () => {
  count.value--;
};
</script>

<template>
  <div>{{ count }}</div>
  <button @click="add">+</button>
  <button @click="sub">-</button>
</template>

<style scoped>
</style>
