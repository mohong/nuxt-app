<template>
  <div class="about">
    about page
  </div>
</template>

<script lang="ts" setup>
  definePageMeta({
    title: 'ddd'
  })

  const route = useRoute()
  console.log(route.meta)

</script>

<style lang="stylus" scoped>

</style>