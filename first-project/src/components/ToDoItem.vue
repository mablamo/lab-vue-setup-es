<script setup>
import { ref } from 'vue';

const msg = ref('nice');
const helloWorldFnc = () => {
  console.log('Hello World!');
};
</script>

<template>
  <div>
    <label for="todo-item"><input type="checkbox" id="todo-item" />My Todo Item {{ msg }}</label>
    <button @click="helloWorldFnc">Hello World!</button>
  </div>
</template>

<style>
</style>
