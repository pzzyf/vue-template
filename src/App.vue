<script setup>
import a from '@/components/1';
const count = ref(0)
</script>

<template>
  <div class="font-size-8">{{ count }}</div>
  <HelloWorld />
  {{ a }}
</template>

<style scoped>
</style>
