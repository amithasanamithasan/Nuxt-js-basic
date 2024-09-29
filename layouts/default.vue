<script lang="ts" setup>

</script>

<template>
    <h1 class="text-5xl font-semibold text-orange-700 ">this is  default layout </h1>
    <div class =" flex justify-end gap-4 my-4 mx-6 text-emerald-900 text-2xl  font-bold">
   
    <RouterLink to="/">Home</RouterLink>
  <RouterLink to="/contact">Contact </RouterLink>
  <RouterLink to="/about">About</RouterLink>
  <RouterLink to="/service">service</RouterLink>
     </div>
  
    <slot></slot>
</template>

<style lang="postcss" scoped>
    
</style>
