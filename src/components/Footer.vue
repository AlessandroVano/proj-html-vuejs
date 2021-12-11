<template>
  <section>  
    <div class="container_1">
      <div class="row ">
        <div class="col-5 text-center">
          <img src="../assets/medical_logo_1x_dark.png" alt="">
             <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium</p>
           <p class="p_1"> doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo</p> 
           <p class="p_2">nventore veritatis et quasi architecto beatae luptatem accusantium.</p> 
           <h5>LEARN MORE ABOUT US</h5>

        </div>
        <div class="col-3">
          <h5>CONTACT INFORMATION</h5>
          <span>121 King Street, London United Kingdom</span>
          <span>1.800.458.556</span>
        </div>
        <div class="col-4">
          <ul>
            <li>
              cardiology
            </li>
            <li>
              cardiology
            </li>
            <li>
              cardiology
            </li>
            <li>
              cardiology
            </li>
            <li>
              cardiology
            </li>
          </ul>

          <button class="btn_1">view our department</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'Footer',

}
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

.container_1 {
  margin-left: 14%;
  padding-top: 50px;
  padding-bottom: 50px;
}
.p_1 {
  margin-left: -52px;
}
.p_2{
  margin-left: -60px;
}

</style>