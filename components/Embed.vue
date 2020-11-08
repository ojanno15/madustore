<template>
    <section class="about" id="about">
        <div class="title-section">
            <h3 class="title-about">Tentang Kami</h3>
            <p class="about-content">Kami adalah penadah madu dari segala daerah di Indonesia, dengan kualitas yang dapat anda percaya, dan harga yang murah untuk pelanggan kesayangan kami.</p>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" allowfullscreen></iframe>
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
    padding-top: 80px;
    background-color: snow;
    padding-bottom: 80px;
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
p.about-content {
    width: 600px;
    margin: auto;
    padding-bottom: 50px;
}
iframe {
    width: 70%!important;
    height: 400px!important;
    border-radius: 10px;
    border: transparent;
    box-shadow: 0px 0px 55px lightblue;
}
@media(max-width: 678px){
    .about {
        width: 100%!important;
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