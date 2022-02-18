<template>
  <div class="my-4">
    <img style="width: 100%" src="../assets/img/banner-category.png" alt="" />
  </div>
  <RelatedItem></RelatedItem>
  <div class="px-5 d-none d-sm-block" style="margin-bottom: 40px">
    <div class="striped-border"></div>
  </div>
  <Description class="d-none d-sm-block"></Description>
</template>

<script>
import RelatedItem from "../components/RelatedItem.vue";
import Description from "../components/Description.vue";

export default {
  components: {
    RelatedItem,
    Description,
  },
  setup() {},
};
</script>

<style scoped>
.striped-border {
  border: 1px dashed #cccccc;
}
</style>
