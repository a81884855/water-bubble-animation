<template>
  <div id="app">
    <Jumbotron />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Jumbotron from "./components/Jumbotron";

export default {
  name: "App",
  components: {
    Jumbotron
  }
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}
</style>
