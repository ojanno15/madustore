<template>
    <div class="container" id="landing-page">
        <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="navbarSupportedContent">
            <div class="container">
                <a class="navbar-brand" @click="toLandingPageElement"> 
                    MaduStore.id
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon">
                    </span>
                </button>
                <div class="collapse  navbar-collapse mr-4" id="navbarNavAltMarkup">
                    <div class="navbar-nav  ml-auto ">
                        <li class="nav-item"><a class="nav-link mr-4" @click="toAboutElement">
                            Proses Kami
                        </a></li>
                        <li class="nav-item"><a class="nav-link mr-4" @click="toTestimoniElement">
                            Testimoni
                        </a></li>
                        <li class="nav-item"><a class="nav-link mr-4" @click="toProductElement">
                            Product
                        </a></li>
                    </div>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    data() {
        return {
            landingpageElement: "",
            aboutElement: "",
            productElement: "",
            testimoniElement: "",
        };
    },
    mounted() {
        this.landingPageElement = document.getElementById("landing-page");
        this.aboutElement = document.getElementById("about");
        this.productElement = document.getElementById("product");
        this.testimoniElement = document.getElementById("testimoni");
    },
    methods: {
        hideMenu() {
            let menuContainer = document.getElementById('navbarNavAltMarkup')
            menuContainer.classList.remove("show")
        },
        toLandingPageElement() {
            this.landingPageElement.scrollIntoView({
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
    },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@600&display=swap');
.navbar {
    background-color:  snow;
    cursor: pointer!important;
    width: 100%!important;
    margin: 0px auto;
    box-shadow: 0 0 16px lightgray;
}
.navigation-bar {
    display: flex;
    justify-content: space-around;
}
.navbar-dark .navbar-brand {
    color: #495057;
}
.navbar-dark .navbar-nav .nav-link {
    cursor: pointer!important;
    color: #495057;
}
.navbar-dark .navbar-brand:hover {
    color: lightgray;
}
.navbar-dark .navbar-nav .nav-link:hover {
    color: lightgrey;
}
</style>