<template>
  <section class="bg">
 <div class="container ">
    <div class="row">
        <div class="text-center distance title_p  ">
           <h2 class="my-2">Make An Appointment</h2>
           <div class="separator">_______________________________</div>
           <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium</p>
           <p> doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo</p> 
           <p>nventore veritatis et quasi architecto beatae</p> 
        </div>
        <div class="container">
            <input type="text">
        </div>
         <div class="container">
            <input type="text">
        </div>
         <div class="container">
            <input type="text">
        </div>
         <div class="container">
            <input type="text">
        </div>
    </div>
 </div>

</section>
</template>

<script>
export default {
 name: 'MakeAnAppointment',
}
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

.bg {
     background-image:  url(../../assets/make-an-appointment.jpg);
    height: 800px;
  background-size: cover;
  background-position-y: -130px;
 }
 .title_p {
   margin-top: 150px;
     color: white;
 }

</style>