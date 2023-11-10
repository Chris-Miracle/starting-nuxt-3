<template>
    <div>
        This is an iphone {{ name }}
    </div>
</template>

<script setup>
const route = useRoute();

const name = computed(() => {
    return route.params.name.replaceAll('-', ' ')
})

useHead({
    title: `Iphone-${route.params.name}`
})

</script>