<script setup>
import NavBar from "@/components/NavBar.vue";
import CarouselComp from "@/components/CarouselComp.vue";
</script>
<template>
  <div class="nome text-center">
    <h1>GR FLIX</h1>
  </div>

  <NavBar />
  <CarouselComp />

  <div class="container text-light" id="filmes">
    <h2>FILMES</h2>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-md-3">
        <img src="@/assets/img/homem aranha.jpg" class="img-fluid" alt="..." />
      </div>
      <div class="col-md-3">
        <img src="@/assets/img/transformers.jpg" class="img-fluid" alt="..." />
      </div>
      <div class="col-md-3">
        <img src="@/assets/img/birdbox.jpg" class="img-fluid" alt="..." />
      </div>
      <div class="col-md-3">
        <img
          src="@/assets/img/velozes e furiosos.jpg"
          class="img-fluid"
          alt="..."
          width="280"
        />
      </div>
    </div>
  </div>
  <br />
  <div class="container text-light" id="series">
    <h2>SÉRIES</h2>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-md-3">
        <img
          src="@/assets/img/twd.jpg"
          class="img-fluid"
          alt="..."
          width="1000"
        />
      </div>
      <div class="col-md-3">
        <img src="@/assets/img/GOT.jpg" class="img-fluid" alt="..." />
      </div>
    </div>
    <div class="col-md-3">
      <img src="@/assets/img/the 100.jfif" class="img-fluid" alt="..." />
    </div>
    <div class="col-md-3">
      <img
        src="@/assets/img/perdidos no espaço.jpg"
        class="img-fluid"
        alt="..."
      />
    </div>
  </div>
</template>
