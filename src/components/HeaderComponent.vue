<template>
    <v-container>
      <v-row>
        <v-col cols="12" class="d-flex justify-center" style="background-color: black;">
          <img class="head" src="../img/head.jpeg" alt="">
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" class="d-flex justify-center" style="background-color: black; color: white">
          <h1>ciaociaociao</h1>
        </v-col>
      </v-row>
      <v-row style="background-color: black">
      <v-col cols="3" class="d-flex align-center justify-center pt-5" style="background-color: black; color: white">
        <span><img src="../img/icons/icons8-mappa-50.png" alt=""></span>
      </v-col>
      <v-col cols="9" class="d-flex align-center" style="background-color: black; color: white">
        <h3 style="white-space: nowrap; margin: 0 auto;">Parco Lago di Cerano - Torre Cajetani (FR)</h3>
      </v-col>
    </v-row>
    </v-container>
  </template>
  
  <script>
  export default {
    name: 'HeaderComponent'
  }
  </script>
  
  <style scoped>
  .head {
    width: 80%;
    height:200px;
  }
  </style>
  