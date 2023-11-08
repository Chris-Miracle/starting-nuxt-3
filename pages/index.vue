<template>
    <div>   
        This is Home page

        <button @click="takeToabout">Move to about</button>
    </div>
</template>

<script setup>

function takeToabout(){
    navigateTo('/about')
}

</script>