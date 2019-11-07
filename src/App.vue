<template>
  <div id="app">
        <Inicio msg="PIEDRA PAPEL O TIJERA"/>
    <button type="button" class="btn btn-dark">Comenzar juego!</button>
   
  </div>
</template>

<script>
import Inicio from './components/Inicio.vue'

export default {
  name: 'app',
  components: {
    Inicio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
