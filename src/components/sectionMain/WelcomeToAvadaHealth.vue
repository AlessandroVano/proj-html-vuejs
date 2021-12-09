<template>
 <div class="container text-center my-5 contenitore_testo">
   <div class="row">  
    <!-- title + p -->
      <section class="text-center col-6 title_p">
          <h4>Welcome to Avada Health</h4>
          <p class="p-2">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo </p>
      </section> 
    <!-- sezione icon + text + p -->
      <section class="d-flex my-5 distance">
        <div v-for="(card, index) in cards" :key="`card ${index}`">
          <CardAvadaHealth :url="card.img" :title="card.title" :text="card.text" />
        </div>
  
      </section>
    </div>
  </div>
</template>

<script>
import CardAvadaHealth from '@/components/card/CardAvadaHealth.vue'
import {IconAvadaHealth} from '@/devData/arrayGeneral.js'

export default {
    name: 'WelcomeToAvadaHealth',
    components: {
      CardAvadaHealth,
    },

    data() {
      return {
        cards: IconAvadaHealth,
      };
    },
};
</script>

<style scoped lang="scss">
@import '@/styles/globals';
@import '@/styles/utilities';

.title_p {
  margin-left: 25%; 
}
</style>