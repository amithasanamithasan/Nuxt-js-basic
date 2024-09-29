<script lang="ts" setup>
import About from '~/component/About.vue';
definePageMeta({
    layouts: 'aboutlayout'
})
useHead({
    title:'About page'
})
</script>

<template>

    <div> 
        
        <h1 class="text-orange-500"> this is About pages</h1>


        <footer>
            <div>
                <h1 class="text-2xl bg-lime-300">this footer section </h1>
         <About></About>
            </div>
        </footer>
    </div>
    
</template>
