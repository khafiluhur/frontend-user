<template>
  <!-- Desktop View -->
  <div
    id="carouselExampleControls"
    class="carousel slide slide d-none d-sm-none d-lg-block"
    data-bs-ride="carousel"
    style="margin-top: 40px"
  >
    <div class="carousel-indicators custome-carousel px-5">
      <button
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide-to="0"
        class="active custome-button"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        class="custome-button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        class="custome-button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
      <button
        type="button"
        class="custome-button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide-to="3"
        aria-label="Slide 4"
      ></button>
    </div>
    <div class="carousel-inner px-5">
      <div class="carousel-item active">
        <div class="row">
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/c/u/cuan_number_one_sale_main_banner_.jpg"
              alt="1 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/m/s/mshop_banjir_emas_main_banner_.jpg"
              alt="2 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/p/r/promo_visio_vision_double_best_promo_main_banner_.jpg"
              alt="3 slide"
            />
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="row">
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/e/m/emshop_x_tokopedia_main_banner_.jpg"
              alt="1 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/b/l/blankenheim_kolase.jpg"
              alt="2 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/s/u/super_sale_banner_sliding_opt_1.jpg"
              alt="3 slide"
            />
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="row">
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/u/n/unbelieveable_discount_main_banner_.jpg"
              alt="1 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/p/r/promo_visio_plus_it_s_loyal_time_main_banner__1.jpg"
              alt="2 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/b/a/banner_lock_n_lock_rose_gold_new_.jpg"
              alt="3 slide"
            />
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <div class="row">
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/u/n/untitled_design.jpg"
              alt="1 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/p/r/promo_visio_plus_it_s_loyal_time_main_banner__1.jpg"
              alt="2 slide"
            />
          </div>
          <div class="col p-0">
            <img
              class="banner-emshop"
              src="https://emshop.id/media/mageplaza/bannerslider/banner/image/b/a/banner_lock_n_lock_rose_gold_new_.jpg"
              alt="3 slide"
            />
          </div>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev btn-prev"
      type="button"
      data-bs-target="#carouselExampleControls"
      data-bs-slide="prev"
    >
      <div>
        <span class="" aria-hidden="true">
          <i class="fa-solid fa-arrow-left fa-xl" style="color: black"></i>
        </span>
        <span class="visually-hidden">Previous</span>
      </div>
    </button>
    <button
      class="carousel-control-next btn-next"
      type="button"
      data-bs-target="#carouselExampleControls"
      data-bs-slide="next"
    >
      <span class="" aria-hidden="true">
        <i class="fa-solid fa-arrow-right fa-xl" style="color: black"></i>
      </span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <!-- Mobile View -->
  <div
    id="carouselExampleControls5"
    class="carousel slide d-sm-block d-lg-none"
    data-bs-ride="carousel"
  >
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          style="width: 100%"
          src="https://emshop.id/media/mageplaza/bannerslider/banner/image/c/u/cuan_number_one_sale_main_banner_.jpg"
          alt="1 slide"
        />
      </div>
      <div class="carousel-item">
        <img
          style="width: 100%"
          src="https://emshop.id/media/mageplaza/bannerslider/banner/image/m/s/mshop_banjir_emas_main_banner_.jpg"
          alt="2 slide"
        />
      </div>
      <div class="carousel-item">
        <img
          style="width: 100%"
          src="https://emshop.id/media/mageplaza/bannerslider/banner/image/p/r/promo_visio_vision_double_best_promo_main_banner_.jpg"
          alt="3 slide"
        />
      </div>
    </div>
    <!-- <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleControls5"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button> -->
    <!-- <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleControls5"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button> -->
  </div>
</template>

<script>
// import ItemBanner from "./ItemBanner.vue";

export default {
  name: "Banner",
  components: {
    // ItemBanner,
  },
};
</script>

<style scoped>
.btn-prev {
  background-color: white;
  height: 16%;
  width: 3%;
  top: 40%;
  left: 4%;
  border-radius: 50%;
}
.btn-next {
  background-color: white;
  height: 16%;
  width: 3%;
  top: 40%;
  right: 4%;
  border-radius: 50%;
}
.banner-emshop {
  width: 94%;
  border-radius: 16px;
}
.custome-carousel {
  margin-bottom: 0px;
  margin-left: 0px;
  right: unset;
  bottom: -36px;
}
.custome-button {
  height: 10px;
  width: 10px;
  border-radius: 50%;
  background-color: #cccccc;
  opacity: 1;
}
.carousel-indicators .active {
  width: 28px;
  border-radius: 35px;
  background-color: #f37727;
}
</style>
