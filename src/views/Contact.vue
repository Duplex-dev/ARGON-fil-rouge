<template>
  <div>
    <b-carousel id="carousel1" controls indicators>
      <!-- Text slides with image -->
      <b-carousel-slide img-src="img/Fil Rouge/Main.jpg"> </b-carousel-slide>

      <b-carousel-slide caption text img-src="img/Fil Rouge/logo.jpg">
      </b-carousel-slide>

      <b-carousel-slide img-src="img/Fil Rouge/cosmetics1.jpg">
      </b-carousel-slide>
    </b-carousel>
    <!-- integration d'un carousel -->

    <div class="head-contact">
      <h2>Contactez-nous</h2>
      <p>
        She.Only vous apporte son expertise son savoir-faire en vous proposant
        tout un ensemble de pinceaux à poils naturels et synthétiques ainsi que
        des accéssoires de maquillage et du petits matériels afin de sublimer
        votre maquillage.
      </p>
    </div>

    <div class="contact.section">
      <form class="contact-form" action="page2.html" method="POST">
        <p>
          Vous avez une question? Une suggestion? Contactez-nous et nous serons
          heureux de vous aider!
        </p>
        <input type="text" class="contact-form-text" placeholder="Votre nom" />
        <input
          type="Votre Email"
          class="contact-form-text"
          placeholder="Votre email"
        />
        <input
          type="text"
          class="contact-form-text"
          placeholder="Votre téléphone"
        />
        <textarea
          class="contact-form-text"
          placeholder="Votre méssage"
        ></textarea>
        <input
          type="submit"
          class="contact-form-btn"
          value="Envoyez votre méssage"
        />
      </form>
    </div>
  </div>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  name: "contact",
  components: {
    BCarousel,
    BCarouselSlide,
  },
};
</script>