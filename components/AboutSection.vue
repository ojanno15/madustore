<template>
    <section class="about" id="about">
        <div class="title-section">
            <h3 class="title-about">Ayo Kunjungi Peternakan Kami</h3>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/wW8W76OEHiE" allowfullscreen></iframe>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.about {
    width: 100%!important;
    padding-top: 60px;
    margin: 0px auto;
    margin-bottom: 238px!important;
    background-color: #fee274;
    border-bottom-left-radius: 20%;
    border-bottom-right-radius: 20%;
    height: 21.875rem;
    color: white;
}
.title-about {
    letter-spacing: 1px;
}
.title-about::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: white;
}
.row {
    text-align: center;
}
.title-section {
    text-align: center;
    width: 100%!important;
}
iframe {
    width: 70%!important;
    height: 400px!important;
    border-radius: 10px;
    border: transparent;
    box-shadow: 0px 0px 55px lightblue;
    margin-top: 30px !important;
}
iframe:hover {
  opacity: 0.8;
}
@media(max-width: 678px){
    .about {
        width: 100%!important;
        border-bottom-left-radius: 0%!important;
        border-bottom-right-radius: 0%!important;
        margin-bottom: 35px!important;
        padding-top: 48px !important;
    }
    .title-section {
        width: 100%!important;
    }
    iframe {
        width: 90%!important;
        height: 100%!important;
    }
    .about-content {
        width: 100%!important;
    }
}
</style>