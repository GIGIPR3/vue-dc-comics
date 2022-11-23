<template>
  <div id="app">
    
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <NewComponent/>
    
    <MainerSide/>
    


  </div>
</template>

<script>
import NewComponent from './components/NewComponent.vue'
import MainerSide from './components/MainerSide.vue'

export default {
  name: 'App',
  components: {
    NewComponent,
    MainerSide
  }
}
</script>

<style lang="scss">
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

} */

*{
  font-family: 'Roboto Condensed', sans-serif;
  margin: 0%;
}
</style>
