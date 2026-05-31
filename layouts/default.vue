<template>
  <div class="site-shell">
    <slot />
  </div>
</template>

<style scoped>
.site-shell {
  min-height: 100vh;
  background:
    radial-gradient(circle at top right, rgba(250, 192, 90, 0.2), transparent 42%),
    radial-gradient(circle at bottom left, rgba(30, 141, 123, 0.14), transparent 38%),
    linear-gradient(180deg, #f9f6ef 0%, #f4efe4 55%, #f1eadc 100%);
}
</style>
