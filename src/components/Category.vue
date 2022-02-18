<template>
  <div
    class="d-none d-sm-none d-lg-block"
    style="margin-top: 64px; margin-bottom: 20px"
  >
    <div class="row">
      <div class="col">
        <router-link to="/category" style="text-decoration: none">
          <div class="icon-category">
            <img width="56" src="../assets/img/healthcare.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="color: black">Kesehatan</p>
        </router-link>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/beauty.svg" alt="" />
        </div>
        <p class="text-category fw-bold">Kecantikan</p>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/kitchenware.svg" alt="" />
        </div>
        <p class="text-category fw-bold px-5">Peralatan Dapur</p>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/religion.svg" alt="" />
        </div>
        <p class="text-category fw-bold">Religion</p>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/fashion.svg" alt="" />
        </div>
        <p class="text-category fw-bold">Fashion</p>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/electronic.svg" alt="" />
        </div>
        <p class="text-category fw-bold px-5">Elektronik & Gadget</p>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/sport.svg" alt="" />
        </div>
        <p class="text-category fw-bold">Olahraga</p>
      </div>
      <div class="col">
        <div class="icon-category">
          <img width="56" src="../assets/img/home.svg" alt="" />
        </div>
        <p class="text-category fw-bold px-5">Kebutuhan Rumah</p>
      </div>
    </div>
  </div>
  <div
    id="carouselExampleControls3"
    class="carousel slide d-block-sm d-lg-none py-3 px-2"
  >
    <div class="carousel-inner">
      <div class="row">
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/healthcare.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">Kesehatan</p>
        </div>
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/beauty.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">
            Kecantikan
          </p>
        </div>
        <div class="col">
          <div class="icon-category">
            <img width="42" src="../assets/img/kitchenware.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">
            Peralatan Dapur
          </p>
        </div>
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/religion.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">Religion</p>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/fashion.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">Fashion</p>
        </div>
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/electronic.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">
            Elektronik & Gadget
          </p>
        </div>
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/sport.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">Olahraga</p>
        </div>
        <div class="col">
          <div class="icon-category">
            <img width="44" src="../assets/img/home.svg" alt="" />
          </div>
          <p class="text-category fw-bold" style="font-size: 12px">
            Kebutuhan Rumah
          </p>
        </div>
      </div>
    </div>
    <!-- <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleControls3"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button> -->
    <!-- <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleControls3"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button> -->
  </div>
</template>

<script>
export default {
  name: "Category",
  setup() {},
};
</script>

<style scoped>
.text-category {
  font-size: 14px;
}
.icon-category {
  margin-bottom: 24px;
}
</style>
