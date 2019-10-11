<template>
  <header class="main_menu home_menu">
    <div class="ml-4 mr-4">
      <div class="row align-items-center">
        <div class="col-lg-12">
          <nav class="navbar navbar-expand-lg navbar-light">
            <router-link class="navbar-brand" to="/">
              <img src="~/assets/img/logo_afmapath.png" alt="logo" class="img_header" />
            </router-link>

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
                  <router-link class="nav-link" to="/">congrés</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/mot-du-president">Mot du président</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/programme">Programme</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/frais-sponsor">Frais des sponsors</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/frais-client">Frais d’inscription</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/gallery">Gallery</router-link>
                </li>
              </ul>
            </div>

            <router-link class="navbar-brand" to="/">
              <img src="~/assets/img/logo_cnpm.png" class="img_header" alt="logo" />
            </router-link>
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
