<template>
  <h1>{{ JSON.stringify(formValues.test, null, 2) }}</h1>
<form>
    <div class="mb-3">
      <label for="test" class="form-label">anything</label>
      <input type="text" class="form-control" id="test" placeholder="hello" v-model="formValues.test">
      <button @click="post">post it</button>
    </div>
</form>
</template>

<script>
export default {
  name: "Form-one",
  data() {
    return {
      message: "hi",
      formValues:{
        test: ''
      }
        }
      },
  methods: {
    post(){
      console.log('hello')


    }
  }
}
</script>

<style scoped>

</style>