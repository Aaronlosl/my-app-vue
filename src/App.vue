<template>
  <img alt="XY logo" src="./assets/whj/logo.png" width="121.86" height="83.76">
  <HelloWorld msg="Sign in | up to XY"/>
  <img alt="Privacy protocol" src="./assets/whj/Icon.png" width="24" height="24">
  <img alt="Send" src="./assets/whj/Arrow1.png" width="50" height="50">
</template>

<script>
import HelloWorld from './components/whj/HelloWorld.vue'

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
  color: #2c3e50;
  margin-top: 60px;
}
</style>
