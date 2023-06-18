<template>
    <v-container>
      <v-row>
        <v-col cols="12" class="d-flex justify-center pt-10" style="background-color:black; color:white">
          <h1>Info tavoli e prevendite:</h1>
        </v-col>
        <v-col cols="12" class="d-flex justify-center pt-5" style="background-color:black; color:white">
          <v-col cols="12" style="color: white">
            <h1>numero: 303030303030</h1>
          </v-col>          
          <v-col cols="12" class="d-flex justify-center" style="color: white">
            <h1>numero: 303030303030</h1>
          </v-col>          
          <v-col cols="12" class="d-flex justify-center" style="color: white">
            <h1>numero: 303030303030</h1>
          </v-col>          
        </v-col>
      </v-row>
    </v-container>
  </template>
  
  <script>
  export default {
    name: 'BodyComponent',
    data() {
      return {
       items: [
          {
            name: 'Cristian',
            number: '3333333333'
          },
          {
            name: 'Andrea',
            number: '3333333333'
          },
          {
            name: 'Alessandro',
            number: '3333333333'
          },
          {
            name: 'Alessio',
            number: '3333333333'
          },
        
        ]

      }
    }
  }

  
  </script>
  
  <style scoped>

  </style>
  