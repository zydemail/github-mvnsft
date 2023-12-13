<template>
    <div>
        <h1>{{ name }}</h1>
    </div>
    <nuxt-link to="/home">home</nuxt-link>
    <nuxt-link to="/contact">Contact</nuxt-link>
</template>
<script setup lang="ts">
const name = 'about'
</script>
<style scoped lang="scss">
h1 {
    color: red;
}
</style>