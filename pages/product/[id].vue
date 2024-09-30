<style lang="postcss" scoped>
</style>


<template>
    <h1>This is Product pages</h1>
    <div>
    <h1>{{ id}}</h1>
    </div>
</template>

<script lang="ts" setup>
    const{id}= useRoute().params

    definePageMeta({layouts:'product'})
</script>
