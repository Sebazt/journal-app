<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <h1>Hello word</h1>

    <button @click="goToDayBook"  class="btn btn-primary">Primary</button>
    <button @click="goToDayBook"  class="btn btn-secondary">Secondary</button>
    <button @click="goToDayBook"  class="btn btn-success">Success</button>
  </div>
</template>

<script>
// @ is an alias to /src


export default {

  methods:{
    goToDayBook(){
      this.$router.push({name:'no-entry'})
    }
  }
}
</script>
