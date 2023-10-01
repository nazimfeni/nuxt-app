<template>
    <div>
<h1>About page</h1>
<TheHeader />
    </div>
</template>

<script setup>
useHead({
        title: 'About Page',
        meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'About description'
      }
    ],
})


definePageMeta({
  layout: 'aboutlayout',
});

</script>

<style lang="scss" scoped>

</style>