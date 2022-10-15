<template>
  <div>
    <div class="container-fluid header">
      <div class="container">
        <div class="row pt-4 align-items-center text-light">
          <div class="col-6">
            <img src="../assets/logo.png" width="150" />
          </div>
          <div class="col-6">
            <h1>Meat The Difference</h1>
          </div>
        </div>
      </div>
    </div>
    <div class="wave"></div>
  </div>
</template>

<script>
export default {
  name: "HeaderUp",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header {
  background: #74a02d;
}
.wave {
  background-image: url(../assets/wave.svg);
  height: 240px;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
