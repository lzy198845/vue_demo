<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <!-- <HelloWorld msg="Hello Vue in CodeSandbox!"/> -->
    <demo1 msg="123"/>
  </div>
</template>

<script>
import demo1 from "./components/demo1";
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld,
    demo1
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
