<template>
    <div class="container" id="landing-page">
        <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="navbarSupportedContent">
            <div class="container">
                <a class="navbar-brand text-light" @click="toLandingPageElement"> 
                    MaduStore
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon">
                    </span>
                </button>
                <div class="collapse  navbar-collapse mr-4" id="navbarNavAltMarkup">
                    <div class="navbar-nav  ml-auto ">
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toAboutusElement">
                            Tentang Kami
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toProductElement">
                            Produk
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toBenefitElement">
                            Keunggulan
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toTestimoniElement">
                            Testimoni
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toContactElement">
                            Kontak
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
            aboutusElement: "",
            productElement: "",
            benefitElement: "",
            testimoniElement: "",
            contactEelement: "",
        };
    },
    mounted() {
        this.landingPageElement = document.getElementById("landing-page");
        this.aboutusElement = document.getElementById("about");
        this.productElement = document.getElementById("product");
        this.benefitElement = document.getElementById("benefit");
        this.testimoniElement = document.getElementById("testimoni");
        this.contactElement = document.getElementById("contact");
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
        toAboutusElement() {
            this.aboutusElement.scrollIntoView({
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
        toBenefitElement() {
            this.benefitElement.scrollIntoView({
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
        toContactElement() {
            this.contactElement.scrollIntoView({
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
    background-color:  #A2D2FF;
    box-shadow: 0 0 16px #B0D9FF;
    cursor: pointer!important;
}
.navigation-bar {
    display: flex;
    justify-content: space-around;
}
.navbar-dark .navbar-nav .nav-link {
    cursor: pointer!important;
}
</style>