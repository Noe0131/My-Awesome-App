<script setup>
import { ref } from 'vue'
const greeting = ref('Hello World!')
</script>

<template>
  <p class="greeting">{{ greeting }}</p>
</template>

<style>
.greeting {
  color: royalblue;
  font-weight: bold;
  font-size: calc(16px + 2vw);
}
</style>