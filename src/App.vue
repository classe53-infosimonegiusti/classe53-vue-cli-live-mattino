<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Classe 53</h1>
    <MioComponente></MioComponente>
    <MioComponente></MioComponente>
    <MioComponente></MioComponente>
    <MioComponente></MioComponente>

  </div>
</template>

<script>
import MioComponente from './components/MioComponente.vue'

export default {
  name: 'App',
  components: {
    MioComponente
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
