<template>
  <div class="home">
    <div id="app">
    <h1>To-Do List</h1>
  <ul>
    <li>
      <to-do-item></to-do-item>
    </li>
  </ul>
  </div>
  </div>
</template>

<script>
import ToDoItem from '../components/ToDoItem.vue';

export default {
  name: 'HomeView',
  components: {
    ToDoItem,
  },
};
</script>
