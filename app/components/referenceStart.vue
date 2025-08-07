<script setup lang="ts">
const test = shallowRef('Hello, Nuxt!')
</script>

<template>
  <div>
    <h2>Reference Component {{ test }}</h2>
  </div>
</template>
