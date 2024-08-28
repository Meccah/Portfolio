<script setup>
import { RouterView } from "vue-router";
import Header from "./components/Header.vue";
</script>

<template>
  <div class="bg-gray-900 font-mono max-w-7xl mx-auto py-5">
    <Header />
    <div>
      <RouterView />
    </div>
  </div>
</template>

<style scoped></style>
