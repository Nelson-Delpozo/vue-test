<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Favorite Restaurant"/>
  <CountButton/>
  <ListOfTeams/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CountButton from "./components/CountButton";
import ListOfTeams from "@/components/ListOfTeams";

export default {
  name: 'App',
  components: {
    ListOfTeams,
    HelloWorld,
    CountButton,
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
