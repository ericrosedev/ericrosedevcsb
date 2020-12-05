<template>
  <div id="app">
    <img alt="png test" src="./assets/svg/test.png" width="25%" />
    <img alt="svg test" src="test.svg" width="25%" />
    <TestSVG />
    <HelloWorld msg="Hello Vue in CodeSandbox!" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import TestSVG from "./assets/png/test.svg";

export default {
  name: "App",
  components: {
    HelloWorld,
    TestSVG,
  },
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
  background: lightblue url("test.svg") no-repeat left;
  background-size: 200px 200px;
}
</style>
