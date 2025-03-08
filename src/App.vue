<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <header class="mt-2">
    <div class="container">
      <nav class="flex gap-1">
        <RouterLink to="/" class="bg-slate-100 px-4 py-2">Home</RouterLink>
        <RouterLink to="/about" class="bg-slate-100 px-4 py-2">
          About
        </RouterLink>
      </nav>

      <HelloWorld msg="VueJS 3.5 and Tailwind CSS v4.0 QuickStart!" />
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
