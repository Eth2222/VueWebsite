<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <CardTable />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CardTable from './components/CardTable.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    CardTable
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

@import'~bootstrap/dist/css/bootstrap.css';
@import'~material-components-web/dist/material-components-web.css';
</style>
