<script lang="ts" setup>
import ServicesList from '~/component/ServicesList.vue';
import detail from './product/detail.vue';
import Datafatch from '../component/Datafatch';
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

   <Datafatch class="grid grid-cols-4 gap-4 border border-t-2 border-cyan-500"></Datafatch>
</div>
    </div>
</template>

<style lang="postcss" scoped>
    
</style>
