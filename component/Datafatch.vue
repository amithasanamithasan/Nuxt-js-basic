<script lang="ts" setup>
const {data: products} = await useFetch('https://fakestoreapi.com/products',{
    method: 'GET',
})

definePageMeta({
        layouts: 'product'
    })
</script>

<template>
    <h1 class="text-center bg-amber-500 text-5xl">Data Feching</h1>
    <!-- <div class="grid grid-cols-4 gap-4">
        <div v-for="(product,index) in products">
        <table>
            <tr>
                <td class="text-2xl">{{ product.id}}</td>
                <td class="text-2xl"> {{ product.title }}</td>
            </tr>
        </table> -->
        <div>
            <div class="grid grid-cols-4 gap-4">
                <div v-for="p in products">
               <RouterLink to="`/product/${p.id}`">{{ p.title }}</RouterLink>

                </div>

            </div>
        </div>
       


</template>

<style lang="postcss" scoped>
    
</style>
