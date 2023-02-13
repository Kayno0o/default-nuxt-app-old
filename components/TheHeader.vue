<template>
  <header class="w-full px-6 py-2 shadow-md">
    <div class="container mx-auto flex items-center gap-12">
      <NuxtLink class="text-2xl font-bold" to="/">Hello, World !</NuxtLink>

      <TheNavbar />
    </div>
  </header>
</template>

<script lang="ts" setup>
import TheNavbar from './TheNavbar.vue';
</script>
