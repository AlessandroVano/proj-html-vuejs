<template>
  <div class="card m-4">
    <div class="hover">
       <img  :src="require(`../../assets/${url}`)" :alt="title"> 
    </div>
      <h4 class="me-4 mt-4 my-3 px-4"> {{name}} </h4>
       <h5 class="me-4 mb-5 px-4"> {{title}} </h5>
      <p class=" px-4 me-4"> {{text}} </p>
      <div class="px-3">
        <i class="fab fa-facebook-f  mt-4 mb-5  i_1"></i>
        <i class="fab fa-twitter i_2"></i>
        <i class="fab fa-instagram-square i_3"></i>
      </div>
    
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

.i_1 {
  background-color: $bg-color-4;
  padding: 8px 12px 8px 12px;
  color: white;
  margin-right: 7px;
  border-radius: 6px;
  
}
.i_2 {
  background-color: $color-btn;
  padding: 8px 9px 8px 9px;
  color: white;
  margin-right: 7px;
  border-radius: 6px;
  
}

.i_3 {
  background-color: $bg-color-3;
  padding: 8px 9px 8px 9px;
  color: white;
  border-radius: 6px;
  
}
img {
  width: 100%;
}



</style>