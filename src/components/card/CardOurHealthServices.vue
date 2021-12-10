<template>
  <div>
    <img :src="require(`../../assets/${url}`)" :alt="title" />
    <h5 class="my-3">{{ title }}</h5>
    <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "CardOurHealthServices",
  props: {
    url: String,
    title: String,
    text: String,
  },
};
</script>

<style scoped lang="scss">
@import "@/styles/globals";
@import "@/styles/utilities";

p {
  padding-left: 18px;
  font-size: 15px;
}
</style>
