<template>
  <div style="background-color: black;">
    <HeaderComponent />
    <BodyComponent/>
  </div>
</template>

<script>
import HeaderComponent from '../components/HeaderComponent.vue'
import BodyComponent from '@/components/BodyComponent.vue';
export default {
  name: 'HomePage',
  components: {
    HeaderComponent,
    BodyComponent
  }
}
</script>

<style scoped>
/* Stili specifici per questa vista */
</style>
