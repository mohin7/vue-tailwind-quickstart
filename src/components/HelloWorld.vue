<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <h1 class="text-3xl font-bold mt-2">{{ msg }}</h1>
</template>

<style scoped></style>
