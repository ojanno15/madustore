<template>
    <div class="gallery" id="gallery">
        <div class="card-gallery">
            <h3 class="gallery-title">Galleri Kami</h3>
                <div class="container">
                    <div class="card-content row">
                    <div class="card">
                        <img src="../assets/images/madu1.jpg" class="card-img" alt="...">
                    </div>
                    <div class="card">
                        <img src="../assets/images/madu6.jpg" class="card-img" alt="...">
                    </div>
                    <div class="card">
                        <img src="../assets/images/madu5.jpg" class="card-img" alt="...">
                    </div>
                    <div class="card">
                        <img src="../assets/images/madu7.jpg" class="card-img" alt="...">
                    </div>
                    <div class="card">
                        <img src="../assets/images/madu8.jpg" class="card-img" alt="...">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.gallery {
    width: 100%!important;
    height: 40rem!important;
    text-align: center;
    background-color:#ffffff;
    font-weight: 400px;
    margin: 0px auto;
    padding-top: 80px;

}
.gallery-title::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
}
.card-content {
    padding-top: 80px;
    display: flex!important;
    justify-content: center;
}
.card {
    width: 210px!important;
    text-align: center;
    border: 1px solid lightgray;
    border-radius: 280px 280px 280px 280px;
    box-shadow: 0 0 16px lightgray;
}
.card-img {
    width: 204px;
    height: 200px;
    border-radius: 300px;
    margin: 0px auto;
}
@media(max-width: 678px){
    .card {
        height: 100%;
        width: 100%!important;
        padding-bottom: 80px;
        border-bottom:  2px inset #86d0c1!important;
        padding: 0 10px 0 10px;
    }
}
</style>