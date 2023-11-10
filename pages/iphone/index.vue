<template>
    <div class="grid grid-cols-4 gap-4 mt-10">
        <nuxt-link to="/iphone/iphone-15" class="shadow-lg rounded-lg border text-center">
            <h1>Iphone 15</h1>
            <div class="flex justify-center">
                <img  width="200" src="/images/iphone1.jpg" alt="">
            </div>
        </nuxt-link>
        <nuxt-link to="/iphone/iphone-14" class="shadow-lg rounded-lg border text-center">
            <h1>Iphone 14</h1>
            <div class="flex justify-center">
                <img width="200" src="/images/iphone2.jpg" alt="">
            </div>
        </nuxt-link>
    </div>
</template>

<script setup>
    useHead({
        title: 'Iphones',
    })
</script>