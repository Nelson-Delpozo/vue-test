<template>
  <button class="btn btn-danger" @click="increment" v-on:mouseover="count--">
    Count is: {{ count }}
  </button>
  <br>
  <button class="btn btn-danger" @click="alert">
    Click for Alert
  </button>
</template>

<script>
export default {
  name: "CountButton",
  data(){
  return {
    count: 0
  }},
  methods:{
    alert(){
      alert("you clicked that button")
    },
    increment(e){
      console.log("event:", e)
      this.count++
    }
  }
}
</script>

<style scoped>
button{
  background-color: #42b983;
}
</style>