<template>
  <div>
    <div class="container-fluid header">
      <div class="container">
        <div class="row pt-4 align-items-center text-light">
          <div class="col-9 d-flex align-items-center">
            <img src="../assets/logo.png" width="150" />
            <p class="fs-1 ms-5">Meat The Difference</p>
          </div>
          <a
            class="col-3 d-flex justify-content-end text-decoration-none link-light"
            href="https://instagram.com/meatthedifference?igshid=YmMyMTA2M2Y="
            target="_blank"
          >
            <i class="fa-brands fa-instagram fa-3x d-none d-lg-block"></i>
          </a>
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
  margin: -1px;
}
</style>
