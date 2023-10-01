<template>
      <div>
            <h1>This is Product details page</h1>
            <h1>{{ route }}</h1>
      </div>
</template>

<script setup>
const route = useRoute().params.id
</script>

<style lang="scss" scoped>

</style>