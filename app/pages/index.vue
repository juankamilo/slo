<script setup lang="ts">
import NavBar from '~/components/header/navBar.vue'
</script>

<template>
  <div class="grid min-h-dvh grid-rows-[auto_1fr_auto]">
    <header>
      <NavBar />
    </header>
    <main>
      <ReferenceStart />
    </main>
    <footer>
      <p>&copy; My Nuxt App</p>
    </footer>
  </div>
</template>
