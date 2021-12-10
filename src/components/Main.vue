<template>
<div>
  <WelcomeToAvadaHealth />

  <MeetOurDoctors />

  <OurHealthServices />

  <TourOurFacilities />

  <CareDiagnosticsRehabilitation />

  <MakeAnAppointment />
  
</div>
  
</template>

<script>
import WelcomeToAvadaHealth from '@/components/sectionMain/WelcomeToAvadaHealth.vue'
import MeetOurDoctors from '@/components/sectionMain/MeetOurDoctors.vue'
import OurHealthServices from '@/components/sectionMain/OurHealthServices.vue'
import TourOurFacilities from '@/components/sectionMain/TourOurFacilities.vue'
import CareDiagnosticsRehabilitation from '@/components/sectionMain/CareDiagnosticsRehabilitation.vue'
import MakeAnAppointment from '@/components/sectionMain/MakeAnAppointment.vue'

export default {
    name: 'Main',
    components: {
        WelcomeToAvadaHealth,
        MeetOurDoctors,
        OurHealthServices,
        TourOurFacilities,
        CareDiagnosticsRehabilitation,
        MakeAnAppointment,
    }

}
</script>


<style>

</style>