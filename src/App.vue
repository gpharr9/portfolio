<template>
  <nav-bar />
  <router-view />
  <page-footer />
</template>

<script>
import { defineComponent } from "vue";
import NavBar from "./components/NavBar.vue";
import PageFooter from "./components/PageFooter.vue";
export default defineComponent({
  name: "App",
  components: {
    NavBar,
    PageFooter,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
