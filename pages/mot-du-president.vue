<template>
  <div>
    <!-- breadcrumb start-->
    <BreadCrumb name="Mot du Président" />
    <!-- breadcrumb start-->
    <div class="container upper">
      <!--================Blog Area =================-->
      <section class="blog_area single-post-area padding_top">
        <div class="container">
          <div class="row">
            <div class="col-lg-4 comite animated slideInLeft">
              <div class="blog_right_sidebar">
                <aside class="single_sidebar_widget post_category_widget">
                  <ul class="list cat-list">
                    <li class="font-weight-bold color-orange">Président :</li>
                    <li class="color-blue">Mohammed EL IBRAHIMI</li>

                    <li class="font-weight-bold color-orange mt-4">Vice-président :</li>
                    <li class="color-blue">Abdelilah TEBAY</li>
                    <li class="color-blue">Zineb SAYAH</li>
                    <li class="color-blue">Azzeddine MOHAMMADI</li>

                    <li class="font-weight-bold color-orange mt-4">Secrétaire général :</li>
                    <li class="color-blue">Mohamed kebir ERRAMI</li>

                    <li class="font-weight-bold color-orange mt-4">SG adjoint :</li>
                    <li class="color-blue">Bouchra LOTFI</li>

                    <li class="font-weight-bold color-orange mt-4">Trésorier :</li>
                    <li class="color-blue">El Hassan KOUAM</li>

                    <li class="font-weight-bold color-orange mt-4">Trésorier adjoint :</li>
                    <li class="color-blue">Mohammed BOUMEDIENE</li>

                    <li class="font-weight-bold color-orange mt-4">Assesseur :</li>
                    <li class="color-blue">Ferdaous SAHNOUN Abdelkrim MOUMEN Loubna OUTALHA</li>
                  </ul>
                </aside>
              </div>
            </div>
            <div class="col-lg-8 posts-list mdp animated slideInRight">
              <div class="single-post">
                <div class="blog_details">
                  <p class="text-right color-blue">Casablanca le 02 Septembre 2019</p>
                  <p class="text-left color-blue">Chers Partenaires,</p>
                  <p class="excert text-justify color-blue">
                    L’Association Franco-marocaine de Pathologie Thoracique, et le collège des pneumologues libéraux du Maroc ont le plaisir de vous informer et vous inviter à leur 16ème congrès du 24 au 26 octobre 2019, à SAVOY le Grand Hôtel à Marrakech.
                    Le 16ème congrès de l'AFMAPATH revêt encore cette année de nombreuses opportunités qui ne manqueront pas de vous intéresser :
                    - Grand événement de la pneumologie au Maroc,
                    - Conférences et formations de qualité avec un panel de 30 intervenants nationaux et étrangers de renommée,
                    - Thèmes d'actualité : BPCO, Asthme, Allergologie, Sommeil, Cancer bronchique, VNI,
                    - Dimension internationale à travers la participation de nombreux pneumologues, exposants et conférenciers étrangers.
                    La destination de Marrakech et l'Hôtel ont été particulièrement choisis pour vous offrir des espaces d'exposition de haut standing et vous donner tous les moyens de mettre en valeur vos marques. Votre partenariat à la formation continue et votre participation active à la réussite de cet événement sont capitaux à travers :
                    - L’insertion du logo sur les affiches, banderoles, cartables, stylos, bloc-notes, - Annonce presse produit dans les programmes,
                    - Participation stands et espaces laboratoires,
                    - Prises en charges des participants.
                    Le 16ème congrès international de l’AFMAPATH sera pour vous un grand événement de rencontre et de partenariat avec la pneumologie Marocaine.
                    Nous vous prions de bien vouloir accepter, Monsieur le Directeur, les meilleures salutations du bureau de l’AFMAPATH.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--================Blog Area end =================-->
    </div>
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
      title: "AFMAPATH ||Mot Du Président",
      meta: [
        {
          hid: "afmapath",
          name: "Mot Du Président",
          content: "Mot Du Président"
        }
      ]
    };
  }
};
</script>

<style>
.blog_right_sidebar .single_sidebar_widget {
  background: none !important;
}

.blog_right_sidebar .post_category_widget .cat-list li {
  border-bottom: none !important;
  padding-bottom: 0px !important;
}

.blog_right_sidebar .post_category_widget .cat-list li + li {
  padding-top: 0px !important;
}

.blog_right_sidebar .list .cat-list {
  font-family: "Open Sans", sans-serif !important;
}
</style>
