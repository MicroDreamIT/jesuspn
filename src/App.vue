<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{$store.state.message}}</h1>
    <router-view></router-view>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>

<style scoped lang="scss">
  /*@import 'assets/css/app.css';*/

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }


</style>
