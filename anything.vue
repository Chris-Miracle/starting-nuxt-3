<template>
  <div>
    <a href="#" @click="toggleComponent('home')"> Home </a>
    <a href="#" @click="toggleComponent('counter')"> Counter </a>

    <NuxtPage/>


    <LazyIncludesHome v-if="view === 'home'" />
    <LazyIncludesCounter v-if="view === 'counter'" />
  </div>
</template>

<script setup>

const view = ref('home');

function toggleComponent(name) {
  view.value = name;
}

</script>
