<template>
  <div>
    <p>Hello, {{ name }}</p>
  </div>
</template>

<script setup>
const props = defineProps({
  name: String,
});
</script>

<style scoped></style>
