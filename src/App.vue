<template>
  <div id="app">
     <h1>Vuejs Chartjs Materialize</h1>    
     <Chart />
  </div>
</template>

<script>

import Chart from './components/Chart'

export default {
  name: 'App',
  components: {
    Chart
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
