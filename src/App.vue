<template>
  <div id="app">
    <router-link to="/"> Home </router-link> |
    <router-link to="/profile"> Profile </router-link> |
    <router-link to="/contact"> Contact </router-link> |
    <router-link to="/project"> Project </router-link> 
    <br />
    <br />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
