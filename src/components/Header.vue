<template>
  <section>
    <!-- sezione logo e utility -->
    <div class="d-flex header justify-content-between p-4">
      <a href="#">
        <img src="../assets/medical_logo_1x_light.png" alt="medical_logo" />
      </a>

      <div class="d-flex">
        <ul>
          <li v-for="(card, index) in cards" :key="`card ${index}`">
            <CardHeader :text="card" />
          </li>
        </ul>

        <div class="my-3">
          <button class="mx-5 btn_1">
            <span>Make Appointment</span>
          </button>
        </div>
      </div>
    </div>

    <!-- sezione titolo con annesso paragrafo e bottone -->
    <div class="container">
      <div class="row">
        <div class="col-6">
          <h1>Caring <span>For Life</span></h1>
          <p>
            Kind words can be short and easy to speak, but their echoes are
            truly endless. Avada Health focuses on you as if it was our own
            family.
          </p>
          <button class="btn_1">Lean more</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import CardHeader from "@/components/card/CardHeader.vue";
import { arrayHeader } from "@/devData/arrayGeneral.js";
export default {
  name: "Header",

  components: {
    CardHeader,
  },

  data() {
    return {
      cards: arrayHeader,
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

//  Stile sezione logo e utility
section {
  background-image: url(../assets/header-image-homepage.jpg);
  height: 800px;
  background-size: cover;

  img {
    width: 250px;
  }

  ul {
    display: flex;
    list-style: none;
    li {
      padding-left: 2rem;
      margin-top: 1.2rem;
    }
  }
}
// Stile sezione titolo con annesso paragrafo e bottone
.container {
  padding-top: 12%;
  padding-right: 5%;
  padding-bottom: 14%;
  padding-left: 5%;
  margin-bottom: 0px;

  span {
    color: $color-btn;
  }
  p {
    color: $color-text-2;
  }
}
</style>
