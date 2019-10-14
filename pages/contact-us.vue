<template>
  <div>
    <BreadCrumb name="Contactez Nous" />
    <!-- ================ contact section start ================= -->
    <section class="contact-section section_padding">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <h2 class="contact-title color-orange">Contactez-nous</h2>
          </div>
          <div class="col-lg-8">
            <form
              name="contact"
              method="POST"
              data-netlify="true"
              class="form-contact contact_form"
            >
              <p>
                <label>
                  Your Name:
                  <input type="text" name="name" class="form-control" />
                </label>
              </p>
              <p>
                <label>
                  Your Email:
                  <input type="email" name="email" class="form-control" />
                </label>
              </p>
              <p>
                <label>
                  Your Role:
                  <select name="role[]" multiple>
                    <option value="leader">Leader</option>
                    <option value="follower">Follower</option>
                  </select>
                </label>
              </p>
              <p>
                <label>
                  Message:
                  <textarea name="message"></textarea>
                </label>
              </p>
              <p>
                <button type="submit">Send</button>
              </p>
            </form>
            <!--             <form
              class="form-contact contact_form"
              name="contact"
              method="POST"
              data-netlify="true"
            >
              <div class="row">
                <div class="col-sm-6">
                  <div class="form-group">
                    <input class="form-control" name="name" id="name" type="text" />
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="form-group">
                    <input class="form-control" name="email" type="email" />
                  </div>
                </div>
                <div class="col-12">
                  <div class="form-group">
                    <textarea class="form-control w-100" name="message" cols="30" rows="9"></textarea>
                  </div>
                </div>
              </div>
              <div class="form-group mt-3">
                <button type="submit" class="button button-contactForm btn_1">Envoyer Message</button>
              </div>
            </form>-->
          </div>

          <div class="col-lg-4">
            <div class="media contact-info">
              <span class="contact-info__icon">
                <i class="ti-home"></i>
              </span>
              <div class="media-body">
                <h3>5 bis, rue Ibnou Babik, quartier Racine</h3>
                <p>Maârif - Casablanca</p>
              </div>
            </div>
            <div class="media contact-info">
              <span class="contact-info__icon">
                <i class="ti-tablet"></i>
              </span>
              <div class="media-body">
                <h3>05 22 94 08 38</h3>
                <p>Lundi à Vendredi de 9h à 17h</p>
              </div>
            </div>
            <div class="media contact-info">
              <span class="contact-info__icon">
                <i class="ti-email"></i>
              </span>
              <div class="media-body">
                <h3>afmapath@gmail.com</h3>
                <p>Contactez-nous quand vous voulez !</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ================ contact section end ================= -->
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
      title: "AFMAPATH || Contactez Nous",
      meta: [
        {
          hid: "afmapath",
          name: "Contactez Nous",
          content: "Contactez Nous"
        }
      ]
    };
  }
};
</script>

<style>
.button {
  background-color: #ff751a !important;
}

.button:hover {
  background-color: #000080 !important;
}

.form-control:focus {
  border-color: #ff751a !important;
}
</style>
