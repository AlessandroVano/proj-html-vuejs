<template>
  <section class="bg">
    <div class="container">
      <div class="row">
        <div class="text-center distance title_p">
          <h2 class="my-2">Make An Appointment</h2>
          <div class="separator">_______________________________</div>
          <p>
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium
          </p>
          <p>
            doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo
          </p>
          <p>nventore veritatis et quasi architecto beatae</p>
        </div>
        <div class="container">
          <div class="row">
            <div class="d-flex boxes flex-wrap">
              <input class="me-5 mt-5 px-5 py-2" type="text"  placeholder="Name*" />
              <input class="mt-5 px-5" type="text" placeholder="Email*" />
              <input class="me-5 mt-5 px-5 py-2" type="text" placeholder="Phone Number" />
              <input class="mt-5 px-5" type="text" placeholder="Appointment Date" />
              <textarea class="mt-5 px-5 py-2" name="" id="" cols="55" rows="4" placeholder="How can we help?*"></textarea>
            </div>
                <button class="btn_1 mt-5 py-3">Make an appointment</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MakeAnAppointment",
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

.bg {
  background-image: url(../../assets/make-an-appointment.jpg);
  height:1070px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position:center;
  background-position-y: -130px;
  margin-bottom: -130px;
 
}
.title_p {
  margin-top: 150px;
  color: white;
}
 
.boxes {
  width: 80%;
margin-left: 23%;
}
input {
  border: 2px solid $color-text-1;
  background: none;
  color: $color-text-1;
}

textarea {
  border: 2px solid $color-text-1;
  background: none;
  color: $color-text-1;
}
button {
  width: 702px;
  margin-left: 315px;
  
}

</style>
