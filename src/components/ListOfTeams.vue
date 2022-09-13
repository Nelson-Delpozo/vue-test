<template>
  <div v-for="team in teams" :key="team.name">
<h3>{{team.name}}</h3>
  <h5 v-for="driver in team.drivers" :key="driver">{{driver}}</h5>
  </div>
</template>

<script>
export default {
  name: "ListOfTeams",
  data(){
    return{
      teams: [{name:"Alfa-Romeo", drivers:["Bottas", "Zhou"]}, {name:"Ferrari", drivers:["LeClerc", "Sainz"]}, {name:"Red Bull", drivers:["Verstappen", "Perez"]}, {name:"Alpha Tauri", drivers:["Gasley", "Tsunoda"]}, {name:"McLaren", drivers:["Ricciardo", "Norris"]}, {name:"Haas", drivers:["Schumacher", "Magnussen"]}, {name:"Mercedes-Benz", drivers:["Lewis", "Russell"]}, {name:"Alpine", drivers:["Alonso", "Ocon"]}, {name:"Williams", drivers:["DeVries", "Albon"]}, {name:"Aston Martin", drivers:["Stroll", "Vettel"]}]
  }}

}
</script>

<style scoped>

</style>