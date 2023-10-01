<template>
        <Home />
        
   <TheHeader />
   <h2>{{state.number}}</h2>
   <button @click="increment">Increment</button>
   <button @click="decrement" v-if="state.number>1">Decrement</button>
   <button @click="decrement" v-else disabled>Decrement</button><br><br>
    <slot />
  

   
</template>

<script setup>
useHead({
        title: 'Home Page',
        meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Home Page description'
      }
    ],
})

const state =useState(()=>({
        number: 1
}))

const increment = ()=>{
        state.value.number++
}

const decrement = () =>{
        state.value.number--
}
</script>

<style lang="scss" scoped>

</style>