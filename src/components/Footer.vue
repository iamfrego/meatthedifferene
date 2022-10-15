<template>
  <div>
    <img
      src="../assets/wave.svg"
      style="transform: rotateX(180deg) rotateY(180deg); margin-bottom: -1px"
    />
    <footer class="pb-5">
      <div class="container">
        <div
          class="row flex-column flex-lg-row pt-3 justify-content-center justify-content-lg-start"
        >
          <div class="col-lg-4 d-none d-lg-block">
            <img src="../assets/logo.png" width="150" alt="" />
          </div>
          <div
            class="col-lg-4 col-12 text-white justify-content-around justify-content-lg-start mb-4 mb-lg-0"
          >
            <h5 class="text-lg-start text-center">Indirizzo:</h5>
            <span class="d-flex justify-content-lg-start justify-content-center"
              >Tento,Italia</span
            >
          </div>
          <div class="col-12 col-lg-4 text-white">
            <h5 class="text-center text-lg-start">Contatti:</h5>
            <div
              class="d-flex align-items-center justify-content-lg-start justify-content-center"
            >
              <a
                class="text-decoration-none link-light"
                href="https://instagram.com/meatthedifference?igshid=YmMyMTA2M2Y="
                target="_blank"
              >
                <i class="fa-brands fa-instagram fa-3x"></i>
              </a>
              <a
                class="ms-4 link-light email"
                href="mailto:contact@meaththedifference.it"
                target="_blank"
              >
                contact@meaththedifference.it
              </a>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "FooterF",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
footer {
  background: #74a02d;
  .email {
    &:hover {
      cursor: pointer;
      text-decoration: underline;
    }
  }
}

@media only screen and (max-width: 768px) {
  /* For desktop: */
}
</style>
