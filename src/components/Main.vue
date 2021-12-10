<template>
<div>
  <WelcomeToAvadaHealth />

  <MeetOurDoctors />

  <OurHealthServices />
  
</div>
  
</template>

<script>
import WelcomeToAvadaHealth from '@/components/sectionMain/WelcomeToAvadaHealth.vue'
import MeetOurDoctors from '@/components/sectionMain/MeetOurDoctors.vue'
import OurHealthServices from '@/components/sectionMain/OurHealthServices.vue'
export default {
    name: 'Main',
    components: {
        WelcomeToAvadaHealth,
        MeetOurDoctors,
        OurHealthServices,
    }

}
</script>


<style>

</style>