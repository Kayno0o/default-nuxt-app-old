<template>
  <div class="flex min-h-screen flex-col justify-between">
    <TheHeader />

    <div class="container mx-auto px-6">
      <slot />
    </div>

    <TheFooter />
  </div>
</template>
