<script setup>
import { RouterView } from 'vue-router'
import TheSearchSection from './components/TheSearchSection.vue'
</script>

<template>
  <header>
    <TheSearchSection />
  </header>

  <RouterView />
</template>

<style scoped>
</style>
