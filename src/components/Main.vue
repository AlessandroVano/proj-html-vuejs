<template>
<div>
  <WelcomeToAvadaHealth />

  <MeetOurDoctors />
</div>
  
</template>

<script>
import WelcomeToAvadaHealth from '@/components/sectionMain/WelcomeToAvadaHealth.vue'
import MeetOurDoctors from '@/components/sectionMain/MeetOurDoctors.vue'
export default {
    name: 'Main',
    components: {
        WelcomeToAvadaHealth,
        MeetOurDoctors,
    }

}
</script>


<style>

</style>