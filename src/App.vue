<template>
  <div id="app">
    <!-- <img alt="png test" src="./assets/svg/test.png" width="25%" /> -->
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  metaInfo: {
    title: "ericrose.dev",
    meta: [
      { charset: "utf-8" },
      {
        name: "description",
        content: "Stuff I do, tools I use, and methodologies I subscribe to",
      },
      { name: "viewport", content: "width=device-width, initial-scale=1" },
    ],
  },
  components: {
    HelloWorld,
  },
};
</script>

<style>
html,
body,
#app {
  margin: 0;
  padding: 0;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #444f6d;
}
</style>
