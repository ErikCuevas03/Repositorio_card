<script setup>
//importacion del seugundo card 
import Cardprincipal from './Cardprincipal.vue';
//importacion del prmier card 
import card from './card.vue';
</script>

<template>
  <div class="container">
    <div>
      <h1 style="text-align: center;">Mascota</h1>

    </div>
    <!-- INICIO DEL PRIMER ROW -->
   <cardprincipal/>
    <!-- FIN DEL PRIMER ROW -->
    <!-- INICIO DEL SEGUNDO ROW -->
  <card/> 
    <!-- FIN DEL SEGUNDO ROW -->
  </div>
</template>

<style scoped></style>
