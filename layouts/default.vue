<script lang="ts" setup>

</script>

<template>
    <h1 class="text-5xl font-semibold text-orange-700">this is  default layout </h1>
    <RouterLink to="/">Home</RouterLink>
  <RouterLink to="/contact">Contact </RouterLink>
  <RouterLink to="/about">About</RouterLink>
  <RouterLink to="/service">service</RouterLink>
    <slot></slot>
</template>

<style lang="postcss" scoped>
    
</style>
