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
        <p style="text-align: center;">Info Tavoli e Prevendite:</p>
      </v-col>
      <v-col cols="12" class="d-flex justify-center">
        <ul>
          <li>Alessandro: 3487905637</li>
          <li>Alessandro: 3487905637</li>
          <li>Alessandro: 3487905637</li>
          <li>Alessandro: 3487905637</li>
        </ul>
      </v-col>
    </v-row>

  </div>
  </v-container>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}
.container {
  height: 100%;
  width: 100%;
  background-color: black;
  color: #fff;
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
}
</style>
