<script setup lang="ts">
const counter = ref(0);
const increment = () => counter.value++;
const decrement = () => counter.value--;
</script>

<template>
  <div>
    <h1>About page</h1>
    <NuxtLink to="/">Home</NuxtLink>
    <p>Counter: {{ counter }}</p>
    <button @click="increment">+</button>
    <button @click="decrement">-</button>
  </div>
</template>
