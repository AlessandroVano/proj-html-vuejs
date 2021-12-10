<template>
<div>
  <WelcomeToAvadaHealth />

  <MeetOurDoctors />

  <OurHealthServices />

  <TourOurFacilities />
  
</div>
  
</template>

<script>
import WelcomeToAvadaHealth from '@/components/sectionMain/WelcomeToAvadaHealth.vue'
import MeetOurDoctors from '@/components/sectionMain/MeetOurDoctors.vue'
import OurHealthServices from '@/components/sectionMain/OurHealthServices.vue'
import TourOurFacilities from '@/components/sectionMain/TourOurFacilities.vue'

export default {
    name: 'Main',
    components: {
        WelcomeToAvadaHealth,
        MeetOurDoctors,
        OurHealthServices,
        TourOurFacilities,
    }

}
</script>


<style>

</style>