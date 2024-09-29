<style lang="postcss" scoped>
</style>


<template>
    <h1>This is Product pages</h1>
    <div>
    <h1>{{ route}}</h1>
    </div>
</template>

<script lang="ts" setup>
    const route= useRoute().params.id
</script>
