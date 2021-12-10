<template>
  <div class="card  m-4">
       <img  :src="require(`../../assets/${url}`)" :alt="title"> 
      <h4 class="me-4 mt-4 my-3 px-4"> {{name}} </h4>
       <h5 class="me-4 mb-5 px-4"> {{title}} </h5>
      <p class="text-center"> {{text}} </p>
    
  </div>
</template>

<script>
export default {
name:  'CardMeetOurDoctors',
props: {
    url: String,
    name: String,
    title: String,
    text: String, 
 }
}
</script>

<style  scoped lang="scss">
@import '@/styles/globals';
@import '@/styles/utilities';



</style>