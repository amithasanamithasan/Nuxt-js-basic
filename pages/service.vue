<script lang="ts" setup>
import ServicesList from '~/component/ServicesList.vue';
import detail from './product/detail.vue';
useHead({
    title:'Services page'
})
</script>

<template>
    <h1>this is services pages</h1>
    <div>
        <ServicesList></ServicesList>
<div>
   <detail></detail>
</div>
    </div>
</template>

<style lang="postcss" scoped>
    
</style>
