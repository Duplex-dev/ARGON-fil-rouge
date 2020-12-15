<template>
  <!-- <section class="section section-lg section-shaped overflow-hidden my-0"> -->
  <section>
    <b-carousel id="carousel1" controls indicators>
      <!-- Text slides with image -->
      <b-carousel-slide img-src="img/Fil Rouge/Main.jpg"> </b-carousel-slide>

      <b-carousel-slide caption text img-src="img/Fil Rouge/logo.jpg">
      </b-carousel-slide>

      <b-carousel-slide img-src="img/Fil Rouge/cosmetics1.jpg">
      </b-carousel-slide>
    </b-carousel>
    <p></p>

    <b-container class="bv-example-row">
      <div class="row align-items-center">
        <div id="vidéo" class="col-md-6">
          <iframe
            width="350"
            height="250"
            src="https://www.youtube.com/embed/nNBqZjb0VHY?start=1"
            frameborder="0"
            allow="accelerometer; autoplay=1; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
        <div id="Bienvenue" class="col-md-6">
          <p class="welcome">
            She.Only vous apporte son expertise son savoir-faire en vous
            proposant tout un ensemble de pinceaux à poils naturels et
            synthétiques ainsi que des accéssoires de maquillage et du petits
            matériels afin de sublimer votre maquillage.
          </p>
        </div>
      </div>
    </b-container>

    <div class="container-fluid">
      <h3>NOS PRODUITS</h3>
    </div>

    <b-container class="bv-example-row">
      <div class="row justify-content-between">
        <div id="pinceaux" class="col-md-6">
          <button class="btn-pin">PINCEAUX</button>
        </div>
        <div class="row justify-content-between col-md-6">
          <p class="welcome align-self-center">
            Nous vous proposons des pinceaux de meilleures qualités afin que
            vous puissiez avoir un maquillage parfait.
          </p>
        </div>
      </div>
      <!-- <hr class="featurette-divider" /> -->
      <div class="row possibilities justify-content-between">
        <div id="accessoires" class="col-md-6">
          <button class="btn-access">ACCÉSSOIRES</button>
        </div>
        <div class="row justify-content-between col-md-6">
          <p class="welcome align-self-center">
            Trouvez une séléction d’accéssoires nécessaires pour un maquillage
            parfait.
          </p>
        </div>
      </div>
      <!-- <hr class="featurette-divider" /> -->
      <div class="row possibilities justify-content-between">
        <div id="petits-appareils" class="col-md-6">
          <!-- <img src="images/petitsappareils.jpg" width="350" height="350" alt="petits-matériels"> -->
          <button class="btn-pm">PETITS APPAREILS</button>
        </div>
        <div class="row justify-content-between col-md-6">
          <p class="welcome align-self-center">
            Vous trouverez dans cette rubrique du petit matériel uniquement
            séléctionné pour vous afin de que vous soyez belle.
          </p>
        </div>
      </div>
    </b-container>
  </section>
</template>

<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";
import { BCard } from "bootstrap-vue/esm/components/card";
import { BContainer, BCol, BRow } from "bootstrap-vue/esm/components/layout";

export default {
  components: {
    BCarousel,
    BCarouselSlide,
    BCard,
    BContainer,
    BCol,
    BRow,
  },
  data() {
    return {
      message: "Hello vue.js",
    };
  },
};
</script>