<template>
  <div class="container text-center">
    <div class="row">
      <div>
        <section class="text-center">
          <div class="container mt-5">
            <div class="row">
              <div class="text-center distance title_p">
                <img src="../../assets/icon-6.png" alt="" />
                <h2 class="my-2">OUR HEALTH SERVICES</h2>
                <div class="separator">_______________________________</div>
                <p>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                  accusantium
                </p>
                <p>
                  doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
                  illo
                </p>
                <p>nventore veritatis et quasi architecto beatae</p>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>

    <div class="row mt-4">
      <section class="d-flex my-5  distance flex-wrap">
        <div
          class="boxes mt-5"
          v-for="(card, index) in cards"
          :key="`card ${index}`"
        >
          <CardOurHealthServices
            :url="card.img"
            :title="card.title"
            :text="card.text"
          />
        </div>
      </section>
    </div>
  </div>
</template>

<script>
import CardOurHealthServices from "@/components/card/CardOurHealthServices.vue";
import { IconOurHealthServices } from "@/devData/arrayGeneral.js";

export default {
  name: "OurHealthServices",
  components: {
    CardOurHealthServices,
  },
  data() {
    return {
      cards: IconOurHealthServices,
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

.boxes {
  width: calc(100% / 3);
}
</style>
