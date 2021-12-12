<template>
<section>
 <div class="container ">
    <div class="row">
        <div class="text-center distance title_p col-6 mt-5 ">
            <img src="../../assets/icon-5.png" alt="">
           <h2 class="my-2">MEET OUR DOCTORS</h2>
           <div class="separator">_______________________________</div>
           <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium</p>
           <p> doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo</p> 
           <p>nventore veritatis et quasi architecto beatae</p> 
       
        </div>

         <section class="d-flex my-5 distance">
           <div v-for="(card, index) in cards" :key="`card ${index}`">
          <CardMeetOurDoctors :url="card.img" :name="card.name" :title="card.title" :text="card.text" />
           </div>
        </section>

       


    </div>
 </div>

</section>
</template>

<script>
import CardMeetOurDoctors from '@/components/card/CardMeetOurDoctors.vue'
import { IconMeetOurDoctors} from '@/devData/arrayGeneral.js'

export default {
    name: 'MeetOurDoctors',

    components: {
        CardMeetOurDoctors,
    },

     data() {
      return {
        cards: IconMeetOurDoctors,
      };
    },
 };
</script>

<style  scoped lang="scss">
@import '@/styles/globals';
@import '@/styles/utilities';

section {
    background: $bg-color-2;
}


.title_p {
    margin-left: 25%;
}
</style>