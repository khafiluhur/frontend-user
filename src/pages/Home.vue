<template>
  <Banner></Banner>
  <Category></Category>
  <div
    class="d-lg-none d-sm-block"
    style="height: 8px; background-color: #f6f6f6"
  ></div>
  <div class="px-5 d-none d-sm-block" style="margin-bottom: 20px">
    <hr />
  </div>
  <BestSeller></BestSeller>
  <div
    class="d-lg-none d-sm-block"
    style="height: 8px; background-color: #f6f6f6"
  ></div>
  <div class="px-5 d-none d-sm-block" style="margin-bottom: 20px">
    <hr />
  </div>
  <NewItem></NewItem>
  <div
    class="d-sm-block d-lg-none"
    style="height: 8px; background-color: #f6f6f6"
  ></div>
  <div class="px-5 d-none d-sm-block" style="margin-bottom: 40px">
    <hr />
  </div>
  <RelatedItem></RelatedItem>
  <div class="px-5 d-none d-sm-blocke" style="margin-bottom: 40px">
    <div class="striped-border"></div>
  </div>
  <Description class="d-none d-sm-block"></Description>
</template>

<script>
import Banner from "../components/Banner.vue";
import Category from "../components/Category.vue";
import BestSeller from "../components/BestSeller.vue";
import NewItem from "../components/NewItem.vue";
import RelatedItem from "../components/RelatedItem.vue";
import Description from "../components/Description.vue";

export default {
  components: {
    Banner,
    Category,
    BestSeller,
    NewItem,
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
