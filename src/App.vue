<template>
  <div>
    <Header />
    <Main />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
  },
};
</script>

<style lang="scss">
@import "../node_modules/bootstrap/scss/bootstrap.scss";
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");

html,
body {
  font-family: "Quicksand", sans-serif;
}

#app {
  font-family: "Quicksand", sans-serif;
}
</style>
