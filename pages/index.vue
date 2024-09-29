<script lang="ts" setup>
import Datafatch from '~/component/Datafatch.vue';
import Home from '~/component/Home.vue';
useHead({
    title:'Home page'
})
const state = useState(()=>({
    number:1
}))

const increment =()=>{
    state.value.number++
}
const decriment =()=>{

    state.value.number--
}

</script>

<template>
    <div>
<Home></Home>
<Datafatch></Datafatch>

    <h2>{{ state.number }}</h2>
        <button class="bg-yellow-300 text-2xl rounded-lg hover:bg-green-900  " 
        @click="increment" 
         >Increment</button>
      
        <button class="bg-slate-600  rounded-lg  hover:bg-red-900 text-2xl " @click="decriment" v-if="state.number>1">Decrement</button>
        <button class="bg-slate-600  rounded-lg " @click="decriment" v-else=return 0>Decrement</button>
 

    </div>
</template>

<style lang="postcss" scoped>
    
</style>

