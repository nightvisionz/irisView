<template>
  <div id="app">
    <div id="header">
      <h1>test</h1>
    </div>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Vue from 'vue'
import VueMaterial from 'vue-material'
import 'vue-material/dist/vue-material.min.css'
//import 'vue-material/dist/theme/black-green-light.css' // This line here

Vue.use(VueMaterial);

export default {
  name: 'App',
  components: {
    //HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2f502c;
  margin-top: 60px;
}
</style>
