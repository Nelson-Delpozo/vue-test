<template>
  <NavBar/>
  <img alt="Vue logo" src="./assets/logo2.png" height="200">
  <HelloWorld msg="Welcome to Your Favorite Restaurant"/>
  <CountButton/>
  <ListOfTeams/>
  <CountButton/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CountButton from "./components/CountButton";
import ListOfTeams from "@/components/ListOfTeams";
import NavBar from "@/components/NavBar";

export default {
  name: 'App',
  components: {
    NavBar,
    ListOfTeams,
    HelloWorld,
    CountButton,
  }
}
</script>

<style>
#app {
  font-family: 'Stint Ultra Condensed', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}

</style>
