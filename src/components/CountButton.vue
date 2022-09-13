<template>
  <button @click="count++">
    Count is: {{ count }}
  </button>
</template>

<script>
export default {
  name: "CountButton",
  data(){
  return {
    count: 0
  }}
}
</script>

<style scoped>
button{
  background-color: #42b983;
}
</style>