<template>
  <section class="bg">
    <div class="container">
      <div class="row">
        <div class="text-center distance title_p">
          <img src="../../assets/icon-7.png" alt="" />
          <h2 class="my-2">TOUR OUR FACILITIES</h2>
          <div class="separator">_______________________________</div>
          <p>
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium
          </p>
          <p>
            doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo
          </p>
          <p>nventore veritatis et quasi architecto beatae</p>
          <img src="../../assets/play-icon.png" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TourOurFacilities",
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

.bg {
  background-image: url(../../assets/paralax-bg-tour-facilities.jpg);
  height: 800px;
  background-size: cover;
  background-position-y: -130px;
}
.title_p {
  /*  margin-top: calc(100% / 6); */

  margin-top: 150px;
  color: white;
}
</style>
