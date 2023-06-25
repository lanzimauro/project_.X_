<template>
  <v-container>
    <div class="container d-flex justify-center">
      <v-row class="d-flex justify-center align-center">
        <v-col cols="12" class="d-flex justify-center align-center">
          <div style="display: flex; justify-content: center;">
              <img class="immagine" src="./img/head.jpeg" alt="">
            </div>
        </v-col>
        <v-col cols="12" class="d-flex justify-center align-center">
          <p style="text-align: center;"> <a href="https://goo.gl/maps/VGtAhWFPHWSASmUY9" target="_blank">
          <img src="./img/icons/icons8-mappa-50.png" alt="" style="vertical-align:middle">Parco Lago di Cerano - Torre Cajetani (FR)</a></p>
        </v-col>
        <v-col cols="12" class="d-flex justify-center align-center">
          <p style="text-align: center; font-size:x-large; margin-bottom: 30px">Sabato 15.07.23  DJ Set H 22:00</p>
        </v-col>
        <v-col cols="12" class="d-flex justify-center align-center">
          <p style="text-align: center;">Info Prevendite:</p>
        </v-col>
        <v-col cols="12" class="d-flex justify-center">
          <ul>
            <li @click="openWhatsApp('+393487905637')">Alessandro: <br><img src="./img/icons/icons8-whatsapp-48.png" alt="" style="vertical-align:middle"> 3487905637</li>
            <li @click="openWhatsApp('+393772913610')">Alessio: <br><img src="./img/icons/icons8-whatsapp-48.png" alt="" style="vertical-align:middle"> 3772913610</li>
            <li @click="openWhatsApp('+393400035525')">Cristian: <br><img src="./img/icons/icons8-whatsapp-48.png" alt="" style="vertical-align:middle"> 3400035525</li>
            <li @click="openWhatsApp('+393926969497')">Davide: <br><img src="./img/icons/icons8-whatsapp-48.png" alt="" style="vertical-align:middle"> 3926969497</li>
          </ul>
        </v-col>
        <v-col cols="12" class="d-flex justify-center px-2">
              <p style="text-align: center;">Get connected with us! <a href="https://www.instagram.com/project_.x.__/?hl=it" target="_blank"><img src="./img/icons/icons8-instagram-48.png" alt="" style="vertical-align:middle"></a></p>
        </v-col>
        <v-col cols="12" class="d-flex justify-center">
          <div class="foot">
            <p>TURRIS IN FABULA ETS</p>
            <p>turrisinfabula@gmail.com</p>
            <p>C.F: 92094350607</p>
          </div>
        </v-col>
      </v-row>
    </div>
  </v-container>
</template>

<script>

export default {
  name: 'App',
  methods: {
    openWhatsApp(phoneNumber) {
      const url = `https://api.whatsapp.com/send?phone=${encodeURIComponent(phoneNumber)}`;
      window.open(url, '_blank');
    }
  }
}
</script>

<style>

@font-face {
  font-family: 'Bank Gothic';
  src: url('./fonts/Bank-Gothic-Light-Regular.otf') format('truetype'); /* Assicurati di specificare il percorso corretto del tuo file del font */
  /* Altre opzioni di formato del font se necessario */
}
body {
  margin: 0;
  padding: 0;
  overflow-y: scroll;
  background-color: black;
  color: #fff;
  font-family: 'Bank Gothic', sans-serif;
}

p {
  text-align: center;
}


.immagine {
  max-width: 100%;
}

a {
  color: #fff;
}

ul {
  text-align: center;
  margin: auto;
  padding: 0;
  list-style-type: none;
}

li {
  padding-top: 20px;
  font-size: xx-large;
}

.foot {
  width: 100%;
  background-color: #B8B8B8;
}
</style>
