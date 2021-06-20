<template>
  <NavBar />
  <Shop msg="Welcome to Your Vue.js App" />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Shop from "./components/Shop.vue";

export default {
  name: "App",
  components: {
    Shop,
    NavBar,
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
