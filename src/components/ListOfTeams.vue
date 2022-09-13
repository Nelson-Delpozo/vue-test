<template>
<h3 v-for="team in teams" :key="team">{{team}}</h3>
</template>

<script>
export default {
  name: "ListOfTeams",
  data(){
    return{ teams: ["Alfa-Romeo", "Ferrari", "Red Bull", "Alpha-Tauri", "McLaren", "Haas", "Mercedes-Benz", "Alpine", "Williams", "Aston-Martin"]
  }}

}
</script>

<style scoped>

</style>