<template>
  <div>
    <!-- breadcrumb start-->
    <BreadCrumb name="Gallery" />
    <!-- breadcrumb start-->
    <!-- our_service start-->
    <section class="our_service section_padding">
      <div class="container">
        <h3 class="color-orange mb_50">Photos des anciens congrés :</h3>
        <div class="row">
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/1.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/2.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/3.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/4.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/5.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/6.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/7.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/8.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/9.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/10.jpg" alt />
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-xl-4 mb-4">
            <div class="single_feature">
              <div class="single_service">
                <img src="~assets/img/congres/11.jpg" alt />
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
      title: "AFMAPATH ||Gallery",
      meta: [
        {
          hid: "afmapath",
          name: "Gallery",
          content: "Gallery"
        }
      ]
    };
  }
};
</script>

<style>
.section_padding {
  padding: 70px 0px;
}

.single_service {
  min-height: 400px;
}

.our_service .col-sm-6,
.our_service .col-xl-4 {
  margin-top: 0px !important;
}

.our_service .single_service {
  padding: 0 !important;
}

.single_service {
  min-height: 0 !important;
}

.single_service img {
  width: 100%;
  height: 100%;
}

.mb_50 {
  margin-bottom: 50px;
}
</style>
