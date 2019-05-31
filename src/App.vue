<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <CardTable v-bind:projects="projects"/>
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
  },
  data() {
    return {
      projects:[
        {
          id: 1,
          photo: "./src/assets/logo.png",
          title:"my First Project",
          Description: "this is a long description about what was involved. Here is another sentence about things that were required",
          tags: ["Marine", "Coding", "Mechanical Design" ]
        },
        {
          id: 2,
          photo: "./src/assets/logo.png",
          title:"my second Project",
          Description: "this is a long description about what was involved. Here is another sentence about things that were required",
          tags: ["marine", "Coding", "Mechanical Design" ]
        }
      ]
    }
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
