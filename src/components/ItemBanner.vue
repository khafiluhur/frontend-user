<template>
  <div
    v-for="item in 3"
    :key="item"
    class="card"
    style="width: 546px; margin-right: 32px"
  >
    <img
      class="card-img-top"
      src="../assets/img/image3.png"
      alt="Card image cap"
    />
  </div>
</template>

<script>
export default {
  name: "ItemBanner",
};
</script>

<style scoped></style>
