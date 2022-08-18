<script setup>
import { ref } from 'vue';

const msg = ref('nice');
</script>

<template>
  <div>
    <label for="todo-item"
      ><input type="checkbox" id="todo-item" />My Todo Item {{ msg }}</label
    >
  </div>
</template>

<style>
</style>
