<template>
    <div class="our-product" id="product">
        <div class="card-product">
            <h3 class="card-title">Produk Kami</h3>
                <div class="container">
                    <div class="card-content row">
                        <div class="card">
                        <img src="../assets/images/madu kopi.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h3 class="card-title-one">Madu Kopi</h3>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis non repudiandae obcaecati sed molestias,</p>
                        </div>
                        </div>
                        <div class="card">
                            <img src="../assets/images/madu hutan sumbawa.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h3 class="card-title-two">Madu Hutan Sumbawa</h3>
                                <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Natus ea explicabo magnam nam nesciunt!</p>
                            </div>
                        </div>
                        <div class="card">
                        <img src="../assets/images/madu kaliandra.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h3 class="card-title-three">Madu Kaliandra</h3>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum eos ex numquam accusamus adipisci deserunt</p>
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
    height: 40rem;
    text-align: center;
    padding-top: 60px;
    background-color: #BDE0FE;
    font-weight: 400px;

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
    border: 1px solid #B0D9FF;
    border-radius: 20px 20px 20px 20px;
    box-shadow: 0 2px 6px 0 rgba(0,0,0,.2);
    cursor: pointer;
}
.card-body {
    background-color: #f4f4f2;
    border-radius: 0px 0px 20px 20px;
}
.card-title {
    height: 120px;
}
.card-img-top {
    border-radius: 20px 20px 0px 0px;
}
.card-title-one, .card-title-two, .card-title-three {
    font-size: 25px;
    font-weight: 700;
}
@media(max-width: 678px){
    .our-product {
        height: 85rem;
        width: 100%!important;
    }
}
</style>