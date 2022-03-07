<template>
  <div id="app">
    <registro/>
    <login/>
    <navbar/>
  </div>
</template>

<script>
import Registro from './components/sesion/Registro.vue';
import Login from './components/sesion/Login.vue';
import Navbar from './components/Navbar.vue';

export default {
  name: "App",
  components: {
    Registro,
    Login,
    Navbar
  }
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
