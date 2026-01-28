<script setup>
import { ref } from 'vue'

// "ref" makes the variable reactive
const count = ref(0)
</script>

<template>
  <div class="container">
    <button @click="count++">
      Count is: {{ count }}
    </button>
  </div>
</template>

<style scoped>
button {
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 8px;
  border: 1px solid #ccc;
}
</style>