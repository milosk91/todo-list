<template>
  <div class="app">
    <TodoList />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TodoList from '../components/TodoList.vue'
import Router from 'vue-router'

Vue.use(Router)

export default Vue.extend({
  components: {
    TodoList,
  },
})
</script>

<style scoped lang="scss">
* {
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  margin: auto;
}
.app {
  background-color: #d9eff7;
  height: 770px;

  padding-top: 5rem;
}
</style>
