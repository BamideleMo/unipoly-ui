<script setup>
import Menu from "./Menu.vue";
</script>

<template>
  <footer class="bg-slate-950 text-white py-20">
    <div
      class="w-11/12 lg:w-10/12 mx-auto grid grid-cols-1 sm:grid-cols-4 gap-6 lg:gap-10"
    >
      <div class="lg:space-y-3">
        <h2 class="text-lg lg:text-2xl font-bold text-blue-600">Links</h2>
        <Menu class="text-sm grid grid-cols-2 lg:grid-cols-1 gap-6" />
      </div>
      <div class="space-y-3 border-t border-slate-800 pt-3">
        <h2 class="text-lg lg:text-2xl font-bold text-blue-600">
          Phone Contact
        </h2>
        <p>
          <a href="tel:+2348039469095" class="">+234 (0) 8039469095</a>
        </p>
        <p>
          <a href="tel:+2348076925158" class="">+234 (0) 8076925158</a>
        </p>
      </div>
      <div class="space-y-3 border-t border-slate-800 pt-3">
        <h2 class="text-lg lg:text-2xl font-bold text-blue-600">
          Email Contact
        </h2>
        <p>
          <a href="mailto:info@unipoly.edu.ng" target="_blank" class=""
            >info@unipoly.edu.ng</a
          >
        </p>
        <p>
          <a href="mailto:verification@unipoly.edu.ng" target="_blank" class=""
            >verification@unipoly.edu.ng</a
          >
        </p>
      </div>
      <div class="space-y-3 border-t border-slate-800 pt-3">
        <h2 class="text-lg lg:text-2xl font-bold text-blue-600">
          Physical Address
        </h2>
        <p>Gamajigo, Jos, Plateau State, Nigeria.</p>
        <div class="text-xs text-slate-600">
          &copy; 2023. United Polytechnic.
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
