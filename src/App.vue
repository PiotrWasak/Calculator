<template>
  <div id="app">

    <CalcBody />
  </div>
</template>

<script>
import CalcBody from './components/CalcBody.vue'

export default {
  name: 'App',
  components: {
    CalcBody
  }
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
