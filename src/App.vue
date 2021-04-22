<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!---<HelloWorld msg="Welcome to Your Vue.js App"/> --->
    <Count />
    
  </div>
</template>



<script>
//import HelloWorld from './components/HelloWorld.vue'
import Count  from './components/Count.vue'


export default {
  name: 'App',

  components: {
    //HelloWorld,
    Count,
  
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0176eb;
  margin-top: 60px;
  

}
</style>
