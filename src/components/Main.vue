<template>
<div>
  <WelcomeToAvadaHealth />

  <MeetOurDoctors />

  <OurHealthServices />

  <TourOurFacilities />

  <CareDiagnosticsRehabilitation />
  
</div>
  
</template>

<script>
import WelcomeToAvadaHealth from '@/components/sectionMain/WelcomeToAvadaHealth.vue'
import MeetOurDoctors from '@/components/sectionMain/MeetOurDoctors.vue'
import OurHealthServices from '@/components/sectionMain/OurHealthServices.vue'
import TourOurFacilities from '@/components/sectionMain/TourOurFacilities.vue'
import CareDiagnosticsRehabilitation from '@/components/sectionMain/CareDiagnosticsRehabilitation.vue'

export default {
    name: 'Main',
    components: {
        WelcomeToAvadaHealth,
        MeetOurDoctors,
        OurHealthServices,
        TourOurFacilities,
        CareDiagnosticsRehabilitation,
    }

}
</script>


<style>

</style>