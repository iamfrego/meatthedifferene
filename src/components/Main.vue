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
            <div class="fs-4 fw-bold" style="color: #74a02d">Chi Siamo?</div>
            Noi siamo Meat The Difference, siamo studenti universitari che hanno
            un obiettivo comune, combattere il cambiamento climatico. <br />
            È il momento giusto per
            <span class="fw-bolder">CAMBIARE</span>, le nostre abitudini, la
            nostra alimentazione e l’impronta ecologica che ognuno di noi ha sul
            <span class="fw-bolder">PIANETA</span>.
          </span>
        </span>
      </div>
      <div
        class="col-lg-5 col-10 p-5 b_rounded justify-content-center align-items-center bg-white order-lg-4 order-5 text-center"
      >
        <span class="text-center">
          <div class="fs-4 fw-bold" style="color: #74a02d">Mission</div>
          Cambiamo il mondo mangiando.</span
        >
        <br />
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
        <span
          class="fs-2 fw-bolder text-center pt-4 mb-lg-4 mb-3"
          style="color: #74a02d"
          >Perché meglio vegetale?</span
        >
        <div class="row mt-3 justify-content-around flex-column flex-lg-row">
          <div class="col-lg-4 col-12 d-flex mb-3 flex-column">
            <i
              class="fa-solid fa-earth-europe fa-3x me-3 text-center mb-3"
              style="color: #643c26"
            ></i>
            <p class="text-center fs-4">
              Risparmio del <span class="fw-bolder">95%</span> dei terreni
              coltivabili
            </p>
          </div>
          <div class="col-lg-4 col-12 d-flex mb-3 flex-column">
            <i
              class="fa-solid fa-droplet fa-3x me-3 text-center mb-3"
              style="color: #643c26"
            ></i>
            <p class="text-center fs-4">
              Un risparmio dell'<span class="fw-bolder">80%</span> di acqua
            </p>
          </div>
          <div class="col-lg-4 col-12 d-flex mb-3 flex-column">
            <i
              class="fa-solid fa-cow fa-3x me-3 text-center mb-3"
              style="color: #643c26"
            ></i>
            <p class="text-center fs-4">
              Il <span class="fw-bolder">90%</span> in meno di emissioni di gas
              serra
            </p>
          </div>
          <div class="col-12 text-center fs-6 pb-4">
            rispetto alla produzione di carne
          </div>
        </div>
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
