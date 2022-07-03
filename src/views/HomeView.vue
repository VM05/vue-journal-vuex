<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
      <h1>hola mundo</h1>
      <button class="btn btn-primary" @click="goToDaybook">primary</button>
      <button class="btn btn-secondary"  @click="goToDaybook">secondary</button>
      <button class="btn btn-success"  @click="goToDaybook">success</button>
  </div>
</template>

<script>
export default {
  methods:{
    goToDaybook(){
      console.log('hola')
      this.$router.push({ name:'no-entry' })
    },

  }
}
</script>

