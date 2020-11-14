<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top" id="navbar">
    <div class="container">
        <a class="navbar-brand" @click="toNavbarElement"> 
          Maduku.store
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon">
                </span> 
            </button>
            <div class="collapse  navbar-collapse mr-4" id="navbarNavAltMarkup">
                <div class="navbar-nav  ml-auto ">
                    <li class="nav-item"><a class="nav-link mr-4" @click="toAboutElement">
                        Tentang Kami
                    </a></li>
                    <li class="nav-item"><a class="nav-link mr-4" @click="toProductElement">
                        Produk Kami
                    </a></li>
                    <li class="nav-item"><a class="nav-link mr-4" @click="toTestimoniElement">
                        Ulasan
                    </a></li>
                    <li class="nav-item"><a class="nav-link mr-4" @click="toBookingElement">
                        Pemesanan
                    </a></li>
                </div>
            </div>
        </div>
</nav>
</template>

<script>
export default {
  data() {
        return {
            navbarElement: "",
            aboutElement: "",
            productElement: "",
            testimoniElement: "",
            bookingElement: "",
        };
    },
    mounted() {
        this.navbarElement = document.getElementById("navbar");
        this.aboutElement = document.getElementById("about");
        this.productElement = document.getElementById("product");
        this.testimoniElement = document.getElementById("testimoni");
        this.bookingElement = document.getElementById("booking");
    },
    methods: {
        hideMenu() {
            let menuContainer = document.getElementById('navbarNavAltMarkup')
            menuContainer.classList.remove("show")
        },
        toNavbarElement() {
            this.navbarElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
        toAboutElement() {
            this.aboutElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
         toProductElement() {
            this.productElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
        toTestimoniElement() {
            this.testimoniElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
        toBookingElement() {
            this.bookingElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
    },
};
</script>

<style>
.navbar {
  background-color: snow!important;
  width: 100%!important;
  margin: 0px auto;
  box-shadow: 0 0 16px lightgray;
  letter-spacing: 1px;
}
.navbar-brand {
  cursor: pointer;
  color: #495057!important;
}
.navbar-light .navbar-nav .nav-link {
  color: #495057!important;
}
.navbar-light .navbar-nav .nav-link:hover {
  cursor: pointer;
}
</style>