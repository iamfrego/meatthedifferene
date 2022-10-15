<template>
  <div class="container-lg container-fluid mb-5 position-relative">
    <div class="row justify-content-evenly g-lg-5 g-3">
      <div
        class="col-lg-5 col-10 p-5 b_rounded d-flex flex-column justify-content-center align-items-center bg-white order-lg-0 order-1"
      >
        <span class="row flex-lg-row flex-column align-items-center">
          <span class="fs-3 text-center"> Meet the difference </span>
          <span class="fs-3 text-center"> eat it - share it </span>
        </span>

        <i class="fa-solid fa-repeat mt-4 fs-1" style="color: #74a02d"></i>
      </div>
      <div
        class="col-lg-5 col-10 d-flex justify-content-center order-lg-1 order-0"
      >
        <img class="img-fluid" src="../assets/ImgSlogan.png" alt="" />
      </div>
      <div
        class="col-lg-5 col-10 d-flex justify-content-center order-2 mt-5 mb-lg-0"
      >
        <img class="img-fluid" src="../assets/ImgChiSiamo.png" alt="" />
      </div>
      <div
        class="col-lg-5 col-10 p-5 b_rounded d-flex flex-column justify-content-center align-items-center bg-white order-3"
      >
        <span class="row flex-lg-row flex-column align-items-center">
          <span class="text-center">
            Noi siamo Meat The Difference, siamo studenti universitari che hanno
            un obiettivo comune, combattere il cambiamento climatico. <br />
            E’ il momento giusto per
            <span class="fw-bolder">CAMBIARE</span>, le nostre abitudini, la
            nostra alimentazione e l’impronta ecologica che ognuno di noi ha sul
            <span class="fw-bolder">PIANETA</span>.
          </span>
        </span>
      </div>
      <div
        class="col-lg-5 col-10 p-5 b_rounded justify-content-center align-items-center bg-white order-lg-4 order-5"
      >
        <span class="text-center">Cambiamo il mondo mangiando.</span> <br />
        Il nostro obiettivo è <span class="fw-bolder">SENSIBILIZZARE</span> le
        persone sull’impatto ambientale dovuto al consumo di carne da
        allevamento dove gli animali non conducono una vita minimamente
        dignitosa.<br />
        Proponendo un’alternativa di qualità a tutti coloro che vogliono aiutare
        il pianeta tramite un’alimentazione più
        <span class="fw-bolder">SANA</span> ,
        <span class="fw-bolder">CONSAPEVOLE</span> e
        <span class="fw-bolder">SOSTENIBILE</span>.
      </div>
      <div
        class="col-lg-5 col-10 d-flex justify-content-center order-lg-5 order-4 mt-5 mb-lg-0"
      >
        <img class="img-fluid" src="../assets/ImgMission.png" alt="" />
      </div>
      <div
        class="col-10 p-lg-5 p-3 mt-5 b_rounded d-flex flex-column justify-content-center align-items-center bg-white order-last"
      >
        <span class="fs-2 fw-bolder text-center" style="color: #74a02d">
          Perché meglio vegetale?</span
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainM",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.b_rounded {
  border-radius: 5rem;
}
.position-relative {
  top: -50px;
}
</style>
