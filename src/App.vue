<template>
  <div id="app" class="container-fluid mt-3">
    <div class="jumbotron">
      <h1>Parcial NT2 - Gastos Realizados</h1>
      <br>
      <Navbar />
      <router-view></router-view>

    </div>
  </div>
</template>

<script>


import Navbar from './componentes/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
#app {
 
}
</style>
