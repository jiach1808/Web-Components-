<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
      <add></add>
      <text1></text1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import add from './components/add.vue'
import text1 from './components/text1.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
    add,
    text1
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
</style>
