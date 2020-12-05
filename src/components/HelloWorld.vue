<template>
  <div class="hello">
    <p>imagery test continued</p>
    <InlineSvg class="inlinesvg" />
    <img src="../images/ExternalPng.png" alt="" class="externalpng" />
  </div>
</template>

<script>
import InlineSvg from "../components/svg/InlineSvg";

export default {
  name: "HelloWorld",
  components: {
    InlineSvg,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  background: url("https://twxuu.csb.app/ExternalSvg.svg") no-repeat left;
  background-size: 100px 100px;
}
.inlinesvg {
  width: 100px;
}
.externalsvg {
  width: 100px;
  height: 80px;
}
.externalpng {
  width: 100px;
}
</style>
