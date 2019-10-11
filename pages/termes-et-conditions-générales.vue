<template>
  <div>
    <!-- breadcrumb start-->
    <BreadCrumb name="Termes et Conditions Générales" />
    <!-- breadcrumb start-->
    <!-- our_service start-->
    <section class="our_service section_padding">
      <div class="container">
        <h3 style="margin-bottom:50px">Nos termes et conditions générales :</h3>
        <div class="row">
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>01</span>
                <h4>
                  Possibilité de fusionner des stands pour les sponsors qui souhaitent avoir plus de métrage.
                  <br />
                </h4>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>02</span>
                <h4>Les Montants de participation sont fixés selon le métrage et la visibilité des stands : 1er confirmé = 1er servi.</h4>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>03</span>
                <h4>Les maquettes des stands battis doivent être partagés avec l’agence organisatrice 2 semaines avant la date du congrès.</h4>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>04</span>
                <h4>L’agence organisatrice peut s’occuper aussi de la construction des stands pour les sponsors.</h4>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>05</span>
                <h4>Le plan des stands pourrait subir des modifications pour des des raisons logistiques.</h4>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>06</span>
                <h4>Les stands non construits seront équipés de table, 2 chaises, une rallonge multiprise et un projecteur.</h4>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <span>07</span>
                <h4>Un cahier de charge sera envoyé à tout les sponsors pour une meilleure organisation du congrès.</h4>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- our_service part end-->
  </div>
</template>

<script>
import BreadCrumb from "../components/BreadCrumb";
export default {
  components: {
    BreadCrumb
  },
  head() {
    return {
      title: "AFMAPATH ||termes-et-conditions-générales",
      meta: [
        {
          hid: "afmapath",
          name: "termes-et-conditions-générales",
          content: "termes-et-conditions-générales"
        }
      ]
    };
  }
};
</script>

<style>
.single_service {
  min-height: 400px;
}

.our_service .col-sm-6,
.our_service .col-xl-4 {
  margin-top: 0px !important;
}
</style>
