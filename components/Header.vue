<template>
  <header class="main_menu home_menu">
    <div class="ml-4 mr-4">
      <div class="row align-items-center">
        <div class="col-lg-12">
          <nav class="navbar navbar-expand-lg navbar-light">
            <nuxt-link class="navbar-brand" to="/">
              <img src="~/assets/img/logo_afmapath.png" alt="logo" class="img_header" />
            </nuxt-link>

            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="ti-menu"></span>
            </button>
            <div
              class="collapse navbar-collapse main-menu-item justify-content-center animated fadeIn"
              id="navbarSupportedContent"
            >
              <ul class="navbar-nav align-items-center">
                <li class="nav-item">
                  <nuxt-link class="nav-link" to="/">congrés</nuxt-link>
                </li>
                <li class="nav-item">
                  <nuxt-link class="nav-link" to="/mot-du-president">Mot du président</nuxt-link>
                </li>
                <li class="nav-item">
                  <nuxt-link class="nav-link" to="/programme">Programme</nuxt-link>
                </li>
                <li class="nav-item">
                  <nuxt-link class="nav-link" to="/frais-sponsor">Frais des sponsors</nuxt-link>
                </li>
                <li class="nav-item">
                  <nuxt-link class="nav-link" to="/frais-client">Frais d’inscription</nuxt-link>
                </li>
                <li class="nav-item">
                  <nuxt-link class="nav-link" to="/gallery">Gallery</nuxt-link>
                </li>
              </ul>
            </div>

            <nuxt-link class="navbar-brand" to="/">
              <img src="~/assets/img/logo_cnpm.png" class="img_header" alt="logo" />
            </nuxt-link>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style>
.main_menu .main-menu-item ul li .nav-link:focus {
  color: #ff751a;
}

.img_header {
  width: 110px;
  height: 100px;
}
</style>
