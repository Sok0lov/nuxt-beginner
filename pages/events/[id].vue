<template>
  <div>
      event id: {{$route.params.id}}
  </div>
</template>

<script setup>
import {useNuxtApp} from "#app";

const nuxt = useNuxtApp()

console.log(nuxt)

  // const route = useRoute()
  // console.log(route.params.id);
</script>

<style lang="scss" scoped>

</style>