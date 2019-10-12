<template>
  <div>
    <section
      class="breadcrumb breadcrumb_bg align-items-center"
      :style="{ backgroundImage: `url(${backgroundUrl})` }"
    >
      <div class="container">
        <div class="row align-items-center justify-content-between">
          <div class="col-sm-12">
            <div class="breadcrumb_tittle">
              <h3>{{name}}</h3>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import backgroundUrl from "~/assets/banner_bg.png";

export default {
  props: {
    name: String,
    required: true
  },
  data() {
    return { backgroundUrl };
  }
};
</script>
