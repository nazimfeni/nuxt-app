<template>
    <div>
        <slot />
        <nuxt-link to="/" style="padding: 5px;">Home</nuxt-link>
        <nuxt-link to="/about" style="padding: 5px;">About</nuxt-link>
        <nuxt-link to="/contact" style="padding: 5px;">Contact</nuxt-link>
        <nuxt-link to="/portfolio" style="padding: 5px;">Portfolio</nuxt-link>
        
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>