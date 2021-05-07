<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <todos title="Shak's amazing todo list"></todos>
</template>

<script>
import Todos from './components/todos'

export default {
  name: 'App',
  components: {
    Todos
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
