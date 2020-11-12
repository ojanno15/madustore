<template>
    <section class="about" id="about">
        <div class="title-section">
            <h3 class="title-about">Proses Panen Madu Kami</h3>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/E885tzgYvKA" allowfullscreen></iframe>
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
    padding-top: 40px;
    margin: 0px auto;
    margin-bottom: 400px!important;
    background-color: #FBD38D;
    border-bottom-left-radius: 30%;
    border-bottom-right-radius: 30%;
    height: 21.875rem;
}
.title-about::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
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
}
iframe:hover {
  opacity: 0.8;
}
@media(max-width: 678px){
    .about {
        width: 100%!important;
        border-bottom-left-radius: 30%;
        border-bottom-right-radius: 30%;
        margin-bottom: 100px!important;
    }
    .title-section {
        width: 100%!important;
    }
    iframe {
        width: 70%!important;
        height: 100%!important;
    }
    .about-content {
        width: 100%!important;
    }
}
</style>