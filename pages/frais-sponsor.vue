<template>
  <div>
    <!-- breadcrumb start-->
    <BreadCrumb name="Frais de participation des Sponsors" />
    <!-- breadcrumb start-->
    <div class="container">
      <!--table 1-->
      <div class="table-title">
        <h3>Frais de participation des Sponsors</h3>
      </div>
      <table class="table1 table-responsive">
        <thead>
          <tr>
            <td width="30%" class="bckgnd-white"></td>
            <td width="1px" class="bckgnd-white"></td>
            <td width="15%" class="font-weight-bold bckgnd-light">Silver</td>
            <td width="1px" class="bckgnd-white"></td>
            <td width="15%" class="font-weight-bold bckgnd-orange-light">Gold</td>
            <td width="1px" class="bckgnd-white"></td>
            <td width="15%" class="font-weight-bold bckgnd-light">Platinium</td>
            <td width="1px" class="bckgnd-white"></td>
            <td width="15%" class="font-weight-bold bckgnd-orange-light">Symposium</td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td height="1px" class="bckgnd-white" colspan="9"></td>
          </tr>
          <tr>
            <td class="bckgnd-orange-light">
              <p class="font-weight-bold color-blue">Stand</p>
              <span>(Emplacement & superficie selon sponsor)</span>
            </td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-light">6 m²</td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-orange-light">9 m²</td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-light">12 m²</td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-orange-light"></td>
          </tr>
          <tr>
            <td height="1px" class="bckgnd-white" colspan="9"></td>
          </tr>
          <tr>
            <td class="bckgnd-orange-light">
              <p class="font-weight-bold color-blue">Montant</p>
              <span>(MAD)</span>
            </td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-light">30 000</td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-orange-light">40 000</td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-light">60 000</td>
            <td class="bckgnd-white"></td>
            <td class="bckgnd-orange-light">80 000</td>
          </tr>
        </tbody>
      </table>

      <div class="mt-5">
        <div class="table-title">
          <h3>Termes & conditions générales</h3>
        </div>
        <div class="mt-2">
          <ul class="ul">
            <li>Les Montants de participation sont fixés selon le métrage et la visibilité des stands : 1 er confirmé = 1 er servi.</li>
            <li>Possibilité de fusionner des stands pour les sponsors qui souhaitent avoir plus de métrage.</li>
            <li>Les maquettes des stands battis doivent être partagés avec l’agence organisatrice 2 semaines avant la date du congrès.</li>
            <li>L’agence organisatrice peut s’occuper aussi de la construction des stands pour les sponsors.</li>
            <li>Le plan des stands pourrait subir des modifications pour des des raisons logistiques.</li>
            <li>Les stands non construits seront équipés de table, 2 chaises, une rallonge multiprise et un projecteur.</li>
            <li>Un cahier de charge sera envoyé à tout les sponsors pour une meilleure organisation du congrès.</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="row mt_50">
      <div class="col-7"></div>
      <div class="col-5">
        <div class>
          <img src="img/iza_back.png" class="img_back" />
        </div>
        <div class="img_logo">
          <img src="img/iza_logo.png" />
        </div>
      </div>
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
      title: "AFMAPATH ||Frain Sponsor",
      meta: [
        {
          hid: "afmapath",
          name: "Frain Sponsor",
          content: "Frain Sponsor"
        }
      ]
    };
  }
};
</script>

<style>
div.table-title {
  margin-top: 50px;
  margin-bottom: 20px;
  display: block;
  padding: 10px;
  width: auto !important;
  border: 1 solid transparent;
  background-color: #000080 !important;
  display: flex;
  justify-content: center;
  align-items: center;
}

.table-title h3 {
  color: #fafafa;
  font-size: 16px;
  font-weight: 400;
  font-style: normal;
  font-family: "Roboto", helvetica, arial, sans-serif;
  text-shadow: -1px -1px 1px rgba(0, 0, 0, 0.1);
  text-transform: uppercase;
  margin: 0 !important;
}

.ul {
  list-style: none;
  background-color: #f9f9fd;
  padding: 10px;
}

.ul li::before {
  content: "\2022";
  color: #ff751a;
  font-weight: bold;
  display: inline-block;
  font-size: 20px;
  width: 1em;
}

.ul li {
  color: #000080;
  margin-bottom: 5px;
}

/*** Table Styles **/
.table1 {
  background: white;
  border-collapse: collapse;
  margin: auto !important;
  width: 70%;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  animation: float 5s infinite;
}

.table1 tr {
  color: #000080;
  font-size: 16px;
  font-weight: normal;
  text-shadow: 0 1px 1px rgba(256, 256, 256, 0.1);
  border: none;
  text-align: center;
  padding: 5px;
}

.table1 tr:hover td {
  background: #4e5066;
  color: #000080 !important;
  border-top: none;
}

.table1 td {
  padding: 10px;
  text-align: center;
  vertical-align: middle;
  font-weight: 300;
  font-size: 14px;
  text-shadow: -1px -1px 1px rgba(0, 0, 0, 0.1);
}

.table1 th,
td {
  border: none !important;
  text-align: center;
}
</style>
