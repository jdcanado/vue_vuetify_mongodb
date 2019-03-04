<template>
  <div id="app">
    <Toolbar /><img width="25%" src="./assets/logo.png" /> <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Toolbar from "./components/Toolbar";

export default {
  name: "App",
  components: {
    HelloWorld,
    Toolbar
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
