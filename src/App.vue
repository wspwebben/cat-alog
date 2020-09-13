<template>
  <div>{{ test }}</div>
</template>

<script setup>
import { ref } from 'vue';

export const test = ref('Hello World');
</script>