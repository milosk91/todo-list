<template>
  <div class="app">
    <TodoList />
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TodoList from '../components/TodoList.vue'
import Footer from '../components/Footer.vue'
import Router from 'vue-router'

Vue.use(Router)

export default Vue.extend({
  components: {
    TodoList,
    Footer,
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
  max-height: 100%;
  padding-top: 8rem;
  height: 900px;
}
</style>
