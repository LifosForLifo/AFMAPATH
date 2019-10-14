<template>
  <div>
    <!-- banner part start-->
    <section class="banner_part">
      <!-- <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-6 offset-lg-1">
                        <div class="banner_text">
                            <div class="banner_text_iner">
                                <h5>We are digital agency</h5>
                                <h1>Digital and innovative idea</h1>
                                <a href="#" class="btn_1">Explore Work</a>
                            </div>
                        </div>
                    </div>
                </div>
      </div>-->
      <h1>Association Franco Marocaine De Pathologie Thoracique</h1>
    </section>
    <!-- banner part start-->
    <div class>
      <img src="~/assets/img/home.png" alt style="width: 100%" />
    </div>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: "AFMAPATH ||Home",
      meta: [
        {
          hid: "afmapath",
          name: "Home",
          content: "Association Franco Marocaine De Pathologie Thoracique"
        }
      ]
    };
  }
};
</script>
<style scoped>
h1 {
  margin-top: 40px;
  text-align: center;
  color: white;
  text-transform: capitalize;
  font-weight: bold;
  font-size: 70px;
}
@media (max-width: 992px) {
  h1 {
    font-size: 30px;
    margin-top: 80px;
  }
}

.mt {
  margin-top: 100px;
}
</style>
