<template>
<section>
 <div class="container  ">
    <div class="row">
        <div class="text-center distance title_p col-6 ">
            <img src="../../assets/icon-5.png" alt="">
           <h2 class="my-2">Meet our doctors</h2>
           <div class="separator">_______________________________</div>
           <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium</p>
           <p> doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo</p> 
           <p>nventore veritatis et quasi architecto beatae</p> 
        </div>
    </div>
 </div>

</section>
</template>

<script>
export default {
    name: 'MeetOurDoctors',
}
</script>

<style  scoped lang="scss">
@import '@/styles/globals';
@import '@/styles/utilities';

section {
    background: $bg-color-2;
}
.distance {
    margin-top: 6rem;
}

.separator {
    color: #b6b5b5;
   
    margin-bottom: 20px;
}
.title_p {
    margin-left: 25%;
}
</style>