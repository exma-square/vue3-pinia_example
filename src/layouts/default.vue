<template>
  <header>
    <h1>Exaple Pinia</h1>
    <p>The store for Vue</p>
  </header>

  <slot />

  <hr />

  <footer>
  </footer>
</template>

<script setup lang="ts">
import { version as piniaVersion } from 'pinia/package.json'
import { version as vueVersion } from 'vue/package.json'
</script>

<style scoped>
.logo {
  width: 1.5rem;
  height: 1.5rem;
  max-width: 100%;
  margin-bottom: 0;
  color: white;
}
</style>
