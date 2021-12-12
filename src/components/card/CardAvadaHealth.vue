<template>
  <div>
    <div class="a_1">
       <img :src="require(`../../assets/${url}`)" :alt="title"> 
      <h5 class="my-3"> {{title}} </h5>

    </div>
      <p> {{text}} </p>
  </div>
</template>

<script>
export default {
name:  'CardAvadaHealth',
props: {
    url: String,
    title: String,
    text: String, 
 }
}
</script>

<style  scoped lang="scss">
@import '@/styles/globals';
@import '@/styles/utilities';

p {
  padding-left: 18px;
  font-size: 15px;
}
</style>