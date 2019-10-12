<template>
  <!-- footer part start-->
  <footer class="footer-area effect">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-sm-6 col-md-3 col-xl-3">
          <div class="single-footer-widget footer_1">
            <h4 class="color-orange">AFMAPATH</h4>

            <div class="social_icon">
              <a href="#">
                <i class="fa fa-facebook color-blue"></i>
              </a>
              <a href="#">
                <i class="fa fa-twitter color-blue"></i>
              </a>
              <a href="#">
                <i class="fa fa-instagram color-blue"></i>
              </a>
              <a href="#">
                <i class="fa fa-whatsapp color-blue"></i>
              </a>
            </div>
          </div>
        </div>

        <div class="col-xl-3 col-sm-6 col-md-3">
          <div class="single-footer-widget footer_2">
            <h4 class="color-orange">Menu</h4>
            <ul>
              <li>
                <nuxt-link class="color-blue" to="/mot-du-president">Mot du président</nuxt-link>
              </li>
              <li>
                <nuxt-link class="color-blue" to="/programme">Programme</nuxt-link>
              </li>
              <li>
                <nuxt-link
                  class="color-blue"
                  to="/frais-sponsor"
                >Frais de participation des sponsors</nuxt-link>
              </li>
              <li>
                <nuxt-link
                  class="color-blue"
                  to="/frais-client"
                >Frais d’inscription et d’hebergement</nuxt-link>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-xl-3 col-sm-6 col-md-3">
          <div class="single-footer-widget footer_2">
            <h4 class="color-orange">Aide</h4>
            <ul>
              <li>
                <nuxt-link
                  class="color-blue"
                  to="/termes-et-conditions-générales"
                >Termes et conditions</nuxt-link>
              </li>
              <li>
                <nuxt-link class="color-blue" to="/contact-us">Contactez-nous</nuxt-link>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-xl-3 col-sm-6 col-md-3">
          <div class="single-footer-widget footer_2">
            <h4 class="color-orange">Secrétariat de l’AFMAPATH</h4>
            <ul>
              <ul class="color-blue">5 bis, rue Ibnou Babik, quartier Racine, Maârif - Casablanca</ul>
              <ul class="color-blue">Tel : 05 22 94 08 38</ul>
              <ul class="color-blue">Fax : 05 22 94 91 23</ul>
              <ul class="color-blue">Email : afmapath@gmail.com</ul>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12">
          <div class="copyright_part_text text-center">
            <div class="row">
              <div class="col-lg-12">
                <p class="footer-text m-0">
                  <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
                  Copyright &copy;
                  <i class="ti-heart" aria-hidden="true"></i> by
                  <a href="#">LifoForLifos</a>
                  <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <img src="~/assets/img/animate_icon/icon_2.png" class="animation_icon_2" alt />
  </footer>
  <!-- footer part end-->
</template>

<style media="screen">
.footer-area {
  background-color: #fff;
  position: relative;
}

.footer-area .copyright_part_text {
  padding: 0 !important;
  margin-bottom: 10px;
  margin-top: 0px !important;
}

.footer-area .social_icon a {
  cursor: pointer;
}

.effect {
  position: relative;
}
.effect:before,
.effect:after {
  content: "";
  position: absolute;
  z-index: -1;
  -webkit-box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
  -moz-box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
  top: 0;
  bottom: 0;
  left: 10px;
  right: 10px;
  -moz-border-radius: 100px / 10px;
  border-radius: 100px / 10px;
}
.effect:after {
  right: 10px;
  left: auto;
  -webkit-transform: skew(8deg) rotate(3deg);
  -moz-transform: skew(8deg) rotate(3deg);
  -ms-transform: skew(8deg) rotate(3deg);
  -o-transform: skew(8deg) rotate(3deg);
  transform: skew(8deg) rotate(3deg);
}
</style>
