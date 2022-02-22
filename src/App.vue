<template>
  <div id="app">
    <listproducts title="List products"/>
  </div>
</template>

<script>

//import
import Listproducts from './components/Listproducts.vue'

export default {
  name: 'App',
  components: {
    Listproducts
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
