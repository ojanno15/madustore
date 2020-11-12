<template>
    <div class="our-product" id="product">
        <div class="card-product">
            <h3 class="card-title">Produk Kami</h3>
                <div class="container">
                    <div class="card-content row">
                        <div class="card">
                        <img src="../assets/images/madu1.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h3 class="card-title-one">Madu Kopi</h3>
                            <p class="card-text">Madu ternak yang dihasilkan dari nektar bunga kopi yang dihisap oleh lebah madu yang digembalakan diarea perkebunan kopi.</p>
                        </div>
                        </div>
                        <div class="card">
                            <img src="../assets/images/madu2.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h3 class="card-title-two">Madu Hutan Sumbawa</h3>
                                <p class="card-text">Madu ini merupakan madu asli hutan Sumbawa, bukan merupakan madu hasil budidaya.</p>
                            </div>
                        </div>
                        <div class="card">
                        <img src="../assets/images/madu3.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h3 class="card-title-three">Madu Kaliandra</h3>
                            <p class="card-text">Madu yang dihasilkan oleh lebah ternak yang menghisap nektar dari bunga kaliandra dimana wilayah tersebut tumbuh subur bunga kaliandra.</p>
                        </div>
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
.our-product{
    width: 100%!important;
    height: 100%;
    text-align: center;
    background-color:#ffffff;
    font-weight: 400px;
    margin: 0px auto;
    padding-bottom: 60px;

}
.card-title::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
}
.card-content {
    display: flex;
    justify-content: center;
}
.card {
    width: 18rem!important;
    margin: 10px 6px;
    text-align: center;
    border: 1px solid lightgray;
    border-radius: 280px 280px 20px 20px;
    box-shadow: 0 2px 6px 0 rgba(0,0,0,.2);
    cursor: pointer;
}
.card-body {
    background-color: snow;
    border-radius: 0px 0px 20px 20px;
}
.card-title {
    height: 120px;
}
.card-img-top {
    width: 250px;
    height: 260px;
    border-radius: 300px;
    margin: 0px auto;
}
.card-title-one, .card-title-two, .card-title-three {
    font-size: 25px;
    font-weight: 700;
}
@media(max-width: 678px){
    .our-product {
        height: 100%;
        width: 100%!important;
        padding-bottom: 80px;
        border-bottom:  2px inset #86d0c1!important;
    }
}
</style>