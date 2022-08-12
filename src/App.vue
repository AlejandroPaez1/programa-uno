<template>
  <img alt="el logo vue" src="./assets/logo2.png">
  <HelloWorld msg="bienvenido a vue alejandro"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #557fa8;
  margin-top: 60px;
}
</style>
