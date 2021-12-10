<template>
  <section class="d-flex">
    <!--   <div class="bg-1 d-flex">


           <div class="boxes-1">
               <h4>Emergency Care</h4>
               <img src="../../assets/wave-divider.png" alt="">
               <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque</p>
                <button>LEARN MORE</button>
           </div>
       </div>
       <div class="bg-1 d-flex">
           <div class="boxes-1">
               <h4>Emergency Care</h4>
               <img src="../../assets/wave-divider.png" alt="">
               <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque</p>
                <button>LEARN MORE</button>
           </div>
       </div>
       <div class="bg-1 d-flex">
           <div class="boxes-1">
               <h4>Emergency Care</h4>
               <img src="../../assets/wave-divider.png" alt="">
               <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque</p>
                <button>LEARN MORE</button>
           </div>
       </div> -->

    <div class="text-center boxes-1">
      <h4 class="pt-5 pb-2">Emergency Care</h4>
      <img class="pt-1 pb-3" src="../../assets/wave-divider.png" alt="" />
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque
      </p>
      <button class="mt-3 mb-5 px-4 py-2 btn-1">LEARN MORE</button>
    </div>
    <div class="text-center boxes-2">
      <h4 class="pt-5 pb-2">Emergency Care</h4>
      <img class="pt-1 pb-3" src="../../assets/wave-divider.png" alt="" />
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque
      </p>
      <button class="mt-3 mb-5 px-4 py-2 btn-2">LEARN MORE</button>
    </div>
    <div class="text-center boxes-3">
      <h4 class="pt-5 pb-2">Emergency Care</h4>
      <img class="pt-1 pb-3" src="../../assets/wave-divider.png" alt="" />
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque
      </p>
      <button class="mt-3 mb-5 px-4 py-2 btn-3">LEARN MORE</button>
    </div>
  </section>
</template>

<script>
export default {
  name: "CareDiagnosticsRehabilitation",
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";
.boxes-1 {
  background-color: $color-btn;
  .btn-1 {
    background-color: $color-btn;
    color: $color-text-2;
    &.active,
    &:hover {
      background: $color-text-2;
      color: $color-btn;
      transition: color 0.4s;
    }
  }
}
.boxes-2 {
  background-color: $bg-color-3;
  .btn-2 {
    background-color: $bg-color-3;
    color: $color-text-2;
    &.active,
    &:hover {
      background: $color-text-2;
      color: $bg-color-3;
      transition: color 0.4s;
    }
  }
}
.boxes-3 {
  background-color: $bg-color-4;
  .btn-3 {
    background-color: $bg-color-4;
    color: $color-text-2;
    &.active,
    &:hover {
      background: $color-text-2;
      color: $bg-color-4;
      transition: color 0.4s;
    }
  }
}

button {
  border: 2px solid white;
}
</style>
