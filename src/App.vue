<template>
  <Header></Header>
  <router-view></router-view>
  <div class="px-5" style="margin-bottom: 40px">
    <div class="striped-border"></div>
  </div>
  <Footer></Footer>
  <div class="bottom-navigation fixed-bottom px-3 py-3">
    <nav
      class="navbar navbar-expand shadow"
      style="border-radius: 27px; background-color: white"
    >
      <ul class="navbar-nav nav-justified w-100">
        <li class="nav-item">
          <img width="24" src="./assets/img/beranda.svg" alt="" />
          <a href="#" class="nav-link px-0 py-0" style="font-size: 12px">
            Beranda
          </a>
        </li>
        <li class="nav-item">
          <img width="24" src="./assets/img/streaming.svg" alt="" />
          <a
            href="#"
            class="nav-link px-0 py-0"
            style="font-size: 12px; color: #999999"
          >
            Streaming
          </a>
        </li>
        <li class="nav-item">
          <img width="24" src="./assets/img/wishlist1.svg" alt="" />
          <a
            href="#"
            class="nav-link px-0 py-0"
            style="font-size: 12px; color: #999999"
          >
            Wishlist
          </a>
        </li>
        <li class="nav-item">
          <img width="24" src="./assets/img/account.svg" alt="" />
          <a
            href="#"
            class="nav-link px-0 py-0"
            style="font-size: 12px; color: #999999"
          >
            Account
          </a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.striped-border {
  border: 1px dashed #cccccc;
}
@media screen and (min-width: 576px) {
  .bottom-navigation {
    display: none;
  }
}
@media screen and (min-width: 574px) and (max-width: 767px) {
}
</style>
