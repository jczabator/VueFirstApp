<template>
  <div id="app">    
    <HelloWorld msg="Hello Vue!"/>    
    <CurrentDate message="You loaded this page on "/>
    <br>
    <Conditional v-bind:seen="true" />
  </div>     
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CurrentDate from './components/CurrentDate.vue'
import Conditional from './components/Conditional.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    CurrentDate,
    Conditional
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
