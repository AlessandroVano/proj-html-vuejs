<template>
  <section>
    <div class="container">
      <div class="row">
        <div class="col-5">
          <img src="../assets/medical_logo_1x_dark.png" alt="" />
          <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem</p>
          <p>
            doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo
          </p>
          <p>
            nventore veritatis et quasi architecto beatae luptatem accusantium.
          </p>
          <div class="separator">
            ____________________________________________________________
          </div>
          <h5>LEARN MORE ABOUT US</h5>
          <i class="fab fa-facebook-f mt-4 mb-5 i_1"></i>
          <i class="fab fa-twitter i_2"></i>
          <i class="fab fa-youtube i_4"></i>
          <i class="fab fa-instagram-square i_3"></i>
        </div>
        <div class="col-3 ee_1">
          <h5>CONTACT INFORMATION</h5>
          <div class="separator_2">_____</div>
          <p>
            <i class="fas fa-map-marker-alt me-2 i_5 ms-0"></i> 121 King Street,
            London United Kingdom
          </p>
          <p><i class="fas fa-phone me-2 i_5 ms-1"></i>1.800.458.556</p>
        </div>

        <div class="col-3">
          <h5>medical department</h5>
          <div class="separator_2">_____</div>
          <ul>
            <li>
              <i class="fas fa-chevron-right me-1 chevr"></i>
              Cardiology
            </li>
            <li>
              <i class="fas fa-chevron-right me-1 chevr"></i>
              Pediatrics
            </li>
            <li>
              <i class="fas fa-chevron-right me-1 chevr"></i>
              Diabetes Care
            </li>
            <li>
              <i class="fas fa-chevron-right me-1 chevr"></i>
              Pre-natal Care
            </li>
            <li>
              <i class="fas fa-chevron-right me-1 chevr"></i>
              Ultrasound Echocardiogram
            </li>
          </ul>

          <button class="btn_2 mt-3">
            <h5 class="pt-2">view our department</h5>
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

.container {
  padding-top: 50px;
  padding-bottom: 50px;
}
.p_1 {
  margin-left: -52px;
}
.p_2 {
  margin-left: -60px;
}

.ee_1 {
  margin-left: -10px;
  margin-right: 120px;
}
p {
  font-size: 14px;
}
ul {
  padding-left: -2rem;
}
li {
  font-size: 14px;
  list-style: none;
}

img {
  width: 250px;
  margin-bottom: 15px;
}

.i_1 {
  background-color: blue;
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
.i_4 {
  background-color: #cc201f;
  padding: 8px 7px 8px 7px;
  color: white;
  border-radius: 6px;
  margin-right: 7px;
}
.i_5 {
  color: $bg-color-4;
}

.chevr {
  background-color: #3ba5bd;
  padding: 6px 8px 8px 8px;
  color: white;
  border-radius: 50px;
  margin-bottom: 7px;
  font-size: 9px;
}
</style>
