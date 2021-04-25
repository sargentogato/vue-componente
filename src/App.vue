<template>
  <div id="app">
    <h1>Mi primer componete</h1>
    <padre-component />
  </div>
</template>

<script>
import padreComponent from "./components/Padre.vue";

export default {
  name: "App",
  components: {
    padreComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
