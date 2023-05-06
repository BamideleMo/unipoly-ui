<script setup>
import Menu from "./Menu.vue";
</script>

<template>
  <header class="relative z-50">
    <div class="w-10/12 my-4 mx-auto flex">
      <Routerlink to="/" class="w-24 h-24 bg-white p-2 shadow-lg rounded-full">
        <img src="/unipoly-logo.png" class="w-16 mx-auto"
      /></Routerlink>
      <Menu class="flex grow space-x-6 justify-end" />
    </div>
  </header>
</template>

<style scoped></style>
