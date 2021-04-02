<template>
  <div id="app">
    <div id="nav">
      <router-link to="/register">Register</router-link> |
      <router-link to="/DataChart">Data Chart</router-link> |
      <router-link to="/HelloWorld">Doughnut</router-link> |
    </div>
    <!-- <img src="./assets/logo.png"> -->
    <!-- <router-view/> -->
    <div class="container">
      <div class="row">
        <div class="col-12">
          <router-view />
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'App'
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
