<template>
    <div>
        <div class="bg-purple-500 shadow-lg p-3 text-white flex justify-between">
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
            <NuxtLink to="/iphone">Iphones</NuxtLink>
            <NuxtLink to="/profile">Profile</NuxtLink>
        </div>

        <slot></slot>
    </div>
</template>