<template>
  <div class="app-wrap">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Vue from "vue";
import Header from "./components/Header";
import Footer from "./components/Footer";
import Main from "./components/Main";

export default Vue.extend({
  data() {
    return {
      msg: "Hello World!!!",
    };
  },
  components: {
    Header,
    Footer,
    Main,
  },
});
</script>

<style lang="scss" scoped>
.app-wrap {
  height: 100vh;
  width: 100%;
  display: flex;
  flex-direction: column;
}
</style>
