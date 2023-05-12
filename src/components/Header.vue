<script setup>
import { ref } from "vue";
import Menu from "./Menu.vue";

const showMenu = ref(false);

const toggleShowMenu = () => {
  showMenu.value = !showMenu.value;
};
</script>

<template>
  <div
    v-if="showMenu"
    class="bg-black bg-opacity-95 top-0 fixed min-h-screen z-50 w-full flex"
  >
    <div class="grow">&nbsp;</div>
    <div class="w-8/12 bg-white">
      <h2 class="bg-green-600 text-right p-4">
        <span
          @click="toggleShowMenu"
          class="cursor-pointer hover:bg-blue-700 hover:text-white bg-white text-sm uppercase font-semibold p-3 shadow-lg rounded-full text-green-500"
          >Close</span
        >
      </h2>
      <Menu class="space-y-10 p-4" @toggle-show-menu="toggleShowMenu" />
    </div>
  </div>
  <header class="relative z-40">
    <div class="w-11/12 lg:w-10/12 my-2 lg:my-4 mx-auto flex justify-between">
      <RouterLink
        to="/"
        class="w-16 h-16 lg:w-24 lg:h-24 bg-white p-1 lg:p-2 shadow-lg rounded-full"
      >
        <img src="/unipoly-logo.png" class="w-12 lg:w-16 mx-auto"
      /></RouterLink>
      <Menu class="hidden lg:flex lg:grow lg:space-x-6 lg:justify-end" />
      <div class="lg:hidden pt-4">
        <span
          @click="toggleShowMenu"
          class="cursor-pointer hover:bg-blue-700 hover:text-white bg-white text-sm uppercase font-semibold p-3 shadow-lg rounded-full text-green-500"
          >Menu</span
        >
      </div>
    </div>
  </header>
</template>

<style scoped></style>
