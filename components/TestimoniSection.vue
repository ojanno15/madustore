<template>
    <section class="testimoni" id="testimoni">
        <div class="title-section">
            <h3 class="title-testimoni">Sudah Merasakan Madu Sarang Kami?</h3>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/s3Z0GeyH42U" allowfullscreen></iframe>
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
.testimoni {
    width: 100%!important;
    padding-top: 80px;
    background-color: #ffffff;
    padding-bottom: 80px;
    margin: 0px auto;
}
.title-testimoni {
    letter-spacing: 1px;
}
.title-testimoni::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: gray;
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
    box-shadow: 0px 0px 55px #FBD38D;
    margin-top: 60px;
}
@media(max-width: 678px){
    .testimoni {
        width: 100%!important;
    }
    .title-section {
        width: 100%!important;
    }
    iframe {
        width: 70%!important;
        height: 100%!important;
    }
    .testimoni-content {
        width: 100%!important;
    }
}
</style>