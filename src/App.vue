<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <TestComponent url="http://google.com" text="hey hey vueJS" boolean="true" />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";s
import TestComponent from "./components/TestComponent";

export default {
  name: "App",
  components: {
    // HelloWorld,
    TestComponent
  }
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
