<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Favorite Restaurant"/>
  <CountButton/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CountButton from "./components/CountButton";

export default {
  name: 'App',
  components: {
    HelloWorld,
    CountButton
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
