<template>
    <button @click="increment">Increment</button>
    <p>{{ count }}</p>
    <button @click="decrement">Decrement</button>
</template>


<script setup>
const count = ref(0);

function increment (){
  return count.value++;
}

function decrement (){
  return count.value--;
}
</script>