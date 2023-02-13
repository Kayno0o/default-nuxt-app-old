<template>
  <NuxtLink :to="to" class="font-bold text-violet-400">
    <slot />
  </NuxtLink>
</template>

<script>
export default {
  data() {
    return {
      to: String,
    };
  },
};
</script>
