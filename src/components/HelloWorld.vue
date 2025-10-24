<template>
  <div class="card">
    <h2>{{ count }}</h2>
    <button @click="increment">Increment</button>
  </div>
</template>

<script setup>
import { ref } from "vue";

const count = ref(0);

function increment() {
  count.value++;
}
</script>

<style scoped>
.card {
  text-align: center;
  margin-top: 2rem;
}
button {
  padding: 0.5rem 1rem;
  background: #42b983;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}
button:hover {
  background: #369e6f;
}
</style>
