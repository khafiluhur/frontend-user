<template>
  <div class="sticky-top">
    <!-- Desktop View -->
    <nav
      class="navbar navbar-expand-lg navbar-light bg-social px-5 d-none d-sm-block"
    >
      <div class="container-fluid">
        <a class="navbar-brand text-download fw-bold" href="#">
          Download app
        </a>
        <div class="vl" style="margin-right: 16px"></div>
        <div class="collapse navbar-collapse">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <img src="../assets/img/twitter.svg" alt="twitter" />
            </li>
            <li class="nav-item mx-3">
              <img src="../assets/img/facebook.svg" alt="twitter" />
            </li>
            <li class="nav-item5">
              <img src="../assets/img/google.svg" alt="twitter" />
            </li>
          </ul>
          <ul class="navbar-nav mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page">Jadi Mitra</a>
            </li>
            <li class="nav-item mx-3">
              <a class="nav-link active" aria-current="page" href="#"
                >Customer Care</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >Streaming</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <nav
      class="navbar navbar-expand-lg navbar-light bg-main shadow-sm pt-3 pb-3 media-mobile d-none d-sm-block"
    >
      <div class="container-fluid px-5 row">
        <router-link class="navbar-brand mr-1 col" to="/">
          <img
            src="../assets/img/logo.png"
            alt=""
            width="152"
            class="d-inline-block align-text-top"
          />
        </router-link>
        <form class="d-flex d-sm-block d-lg-none col" style="width: 74%">
          <input
            style="
              padding-left: 24px;
              font-size: 12px;
              text-color: #cccccc;
              width: 100%;
            "
            class="form-control search-product"
            type="search"
            placeholder="Cari Produk Kesehatan"
            aria-label="Search"
          />
          <button class="btn btn-outline-search" type="submit">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
        <div class="d-sm-block d-lg-none col">
          <img
            class="align-middle"
            src="../assets/img/wishlist.svg"
            alt="twitter"
          />
        </div>
        <div class="d-sm-block d-lg-none col">
          <img src="../assets/img/cart.svg" alt="twitter" />
        </div>
        <div class="collapse navbar-collapse col" id="navbarSupportedContent">
          <ul class="navbar-nav mb-2 mb-lg-0" style="margin-right: 40px">
            <li class="nav-item dropdown margin-catrgory">
              <a
                class="nav-link text-category text-black"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Kategori
                <i class="fa-solid fa-angle-down"></i>
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <router-link
                    class="dropdown-item"
                    style="text-decoration: none; color: black"
                    to="/category"
                    >Kesehatan</router-link
                  >
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Kecantikan</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Peralatan Dapur</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Religion</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Fashion</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Elektronik & Gadget</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Olahraga</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Kebutuhan Rumah</a>
                </li>
              </ul>
            </li>
            <li class="nav-item margin-main">
              <form class="d-flex">
                <input
                  style="
                    padding-left: 24px;
                    font-size: 12px;
                    text-color: #cccccc;
                  "
                  class="form-control search-product"
                  type="search"
                  placeholder="Cari Produk Kesehatan"
                  aria-label="Search"
                />
                <button class="btn btn-outline-search" type="submit">
                  <i class="fa-solid fa-magnifying-glass"></i>
                </button>
              </form>
            </li>
            <li class="nav-item margin-item my-2">
              <img
                class="align-middle"
                src="../assets/img/wishlist.svg"
                alt="twitter"
              />
            </li>
            <li class="nav-item my-2">
              <img src="../assets/img/cart.svg" alt="twitter" />
            </li>
          </ul>
          <div class="vl" style="margin-right: 40px; height: 30px"></div>
          <button
            class="btn btn-outline-success margin-btn btn-emshop px-5 py-2"
            style="
              background-color: white;
              color: #f37727;
              border-color: #f37727;
            "
            type="submit"
          >
            Masuk
          </button>
          <button
            class="btn btn-outline-success btn-emshop px-5 py-2"
            style="
              background-color: #f37727;
              color: white;
              border-color: #f37727;
            "
            type="submit"
          >
            Daftar
          </button>
        </div>
      </div>
    </nav>
    <!-- Mobile View -->
    <nav
      class="navbar navbar-expand-lg navbar-light bg-main shadow-sm pt-3 pb-3 media-mobile d-lg-none d-sm-block"
    >
      <div class="container-fluid px-3">
        <router-link class="" to="/">
          <img
            src="../assets/img/icon_app.png"
            alt=""
            width="35"
            class="d-inline-block align-text-top mr-0"
          />
        </router-link>
        <form class="d-flex d-sm-block d-lg-none" style="width: 86%">
          <input
            style="
              padding-left: 24px;
              font-size: 12px;
              text-color: #cccccc;
              width: 100%;
            "
            class="form-control search-product"
            type="search"
            placeholder="Cari Produk Kesehatan"
            aria-label="Search"
          />
          <button class="btn btn-outline-search" type="submit">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
        <div class="d-none">
          <img
            class="align-middle"
            src="../assets/img/wishlist.svg"
            alt="twitter"
          />
        </div>
        <div class="d-none">
          <img src="../assets/img/cart.svg" alt="twitter" />
        </div>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mb-2 mb-lg-0" style="margin-right: 40px">
            <li class="nav-item dropdown margin-catrgory">
              <a
                class="nav-link text-category text-black"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Kategori
                <i class="fa-solid fa-angle-down"></i>
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <router-link
                    class="dropdown-item"
                    style="text-decoration: none; color: black"
                    to="/category"
                    >Kesehatan</router-link
                  >
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Kecantikan</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Peralatan Dapur</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Religion</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Fashion</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Elektronik & Gadget</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Olahraga</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Kebutuhan Rumah</a>
                </li>
              </ul>
            </li>
            <li class="nav-item margin-main">
              <form class="d-flex">
                <input
                  style="
                    padding-left: 24px;
                    font-size: 12px;
                    text-color: #cccccc;
                  "
                  class="form-control search-product"
                  type="search"
                  placeholder="Cari Produk Kesehatan"
                  aria-label="Search"
                />
                <button class="btn btn-outline-search" type="submit">
                  <i class="fa-solid fa-magnifying-glass"></i>
                </button>
              </form>
            </li>
            <li class="nav-item margin-item my-2">
              <img
                class="align-middle"
                src="../assets/img/wishlist.svg"
                alt="twitter"
              />
            </li>
            <li class="nav-item my-2">
              <img src="../assets/img/cart.svg" alt="twitter" />
            </li>
          </ul>
          <div class="vl" style="margin-right: 40px; height: 30px"></div>
          <button
            class="btn btn-outline-success margin-btn btn-emshop px-5 py-2"
            style="
              background-color: white;
              color: #f37727;
              border-color: #f37727;
            "
            type="submit"
          >
            Masuk
          </button>
          <button
            class="btn btn-outline-success btn-emshop px-5 py-2"
            style="
              background-color: #f37727;
              color: white;
              border-color: #f37727;
            "
            type="submit"
          >
            Daftar
          </button>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.bg-main {
  background-color: white;
}
.bg-header {
  background-color: blue;
}
.text-download {
  font-size: 14px;
}
.vl {
  border-left: 1px solid #cccccc;
  height: 16px;
}
.bg-social {
  background-color: #f6f6f6;
}
.media-mobile {
  padding-right: 0rem !important;
  padding-left: 0rem !important;
}
.text-category {
  font-size: 16px;
}
.marign-logo {
  margin-right: 64px;
}
.margin-catrgory {
  margin-right: 32px;
}
.search-product {
  width: 589px;
  border-bottom-right-radius: unset;
  border-top-right-radius: unset;
  color: #cccccc;
}
.btn-outline-search {
  border: 1px solid #ced4da;
  border-bottom-left-radius: unset;
  border-top-left-radius: unset;
}
.margin-main {
  margin-right: 42px;
}
.margin-item {
  margin-right: 32px;
}
.margin-btn {
  margin-right: 24px;
}
.btn-emshop {
  font-size: 14px;
}
</style>
