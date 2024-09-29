<script lang="ts" setup>
const {data: products} = await useFetch('https://fakestoreapi.com/products',{
    method: 'GET',
})
</script>

<template>
    <h1 class="text-center bg-amber-500 text-5xl">Data Feching</h1>
    <div v-for="(product,index) in products">
        <table>
            <tr>
                <td class="text-2xl">{{ product.id}}</td>
                <td class="text-2xl"> {{ product.title }}</td>
            </tr>
        </table>
       
    </div>
</template>

<style lang="postcss" scoped>
    
</style>
