<script setup>
import card from './card.vue';
</script>

<template>
  <div class="container">
    <div>
      <h1 style="text-align: center;">Mascota</h1>

    </div>
    <!-- INICIO DEL PRIMER ROW -->
    <div class="row">
      <div class="col-md-6">
        <div class="card ">
          <div class="card-header" style="background-color: #d17b9c;">
            <h6 style="text-align: center; ">Gato</h6>
          </div>
          <div class="card-body d-flex flex-column justify-content-between"
            style="height: 250px ; background-color:#ffd3e2;">
            <div class="d-flex justify-content-center">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlzzSkCT6T9jvFPlHb5ZzU01chrHrTxpurlg&s"
                alt="Gato" class="img-fluid" style="object-fit: cover; max-width: 100%; max-height: 150px;">
            </div>
            <p class="card-text">Los gatos son mamíferos carnívoros, de la familia de los
              félidos, con cuerpo cubierto de pelo, cuatro patas y rabo. Son animales
              inteligentes, ágiles, y tienen un buen olfato, oído y vista. </p>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="card ">
          <div class="card-header" style="background-color: #d17b9c;">
            <h6 style="text-align: center;">Perro</h6>
          </div>
          <div class="card-body d-flex flex-column justify-content-between"
            style="height: 250px; background-color:#ffd3e2;">
            <div class="d-flex justify-content-center">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCcGJVNOMz4kgFILsEvgSaDjlegoPOxOEopA&s"
                alt="perro " class="img-fluid" style="object-fit: cover; max-width: 100%; max-height: 150px;">
            </div>
            <p class="card-text">El perro (Canis familiaris) es un mamífero carnívoro
              doméstico de la familia de los cánidos. Su tamaño, forma y pelaje varían
              según la raza. </p>
          </div>
        </div>
      </div>
    </div>
    <!-- FIN DEL PRIMER ROW -->
    <!-- INICIO DEL SEGUNDO ROW -->
  <card/> 
    <!-- FIN DEL SEGUNDO ROW -->
  <card/>
  </div>
</template>

<style scoped></style>
