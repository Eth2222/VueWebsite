<template>
    <div>
      <div class="container" style="padding 10px">
          <div class="row">
              <div v-bind:key="projects.id" v-for="projects in projects">
                <div style="padding 20px">
                  <CardItem 
                  v-bind:project="projects"
                  
                  />
                </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
import CardItem from "./CardItem"

export default {
    name: "CardTable",
    components:{
      CardItem
    },
    props: ["projects"]
    }


</script>

<style>

</style>


