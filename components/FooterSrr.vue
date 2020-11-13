<template>
    <footer>
        <!-- <section class="footer" id="contact">
            <div class="container">
                <div class="row">
                    <div class="col-md-4 col-sm-6 about-us">
                        <div class="about-us-title">
                            <h4 class="about-us-one">Tentang Kami</h4>
                        </div>
                        <p>Layanan Penjualan Madu Asli Melalui Online. Madu Langsung kami ambil dari Hutan</p>
                        <div class="about-us-media">                     
                            <a href="https://www.facebook.com/nizam.marwadi" target="_blank"><img src="../assets/images/icon fb.png" style="width:40px"></a>
                            <a href="https://www.instagram.com/nizammarwadi/?hl=en" target="_blank"><img src="../assets/images/icon ig.png" style="width:40px"></a>
                            <a href="https://www.facebook.com/nizam.marwadi" target="_blank"><img src="../assets/images/icon fb.png" style="width:40px"></a>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 contact-us">
                        <div class="contact-us-title">
                            <h4 style="list-style-type: none;" class="about-us-two">Kontak Kami</h4>
                        </div>
                        <li class="phone"><a href="https://wa.me/6282362574353" target="_blank">+62823-6257-4353</a></li>
                        <li style="list-style-type: none;">Jl. Prambanan No. 25 Medan Tembung</li>
                        <li style="list-style-type: none;">cs <a href="https://www.instagram.com/nizammarwadi/?hl=en" target="_blank">@madustore</a></li><br>
                        <li style="list-style-type: none;"><b>Jam Operasional</b></li>
                        <li style="list-style-type: none;">Setiap Hari :</li>
                        <li style="list-style-type: none;">08.00 - 20.00</li>
                    </div>
                    <div class="col-md-4 col-sm-6 email-us">
                        <div class="email-us-title">
                            <h4 class="about-us-three">Kirim Email</h4>
                        </div>
                        <p>Kirim Email Anda di bawah ini, untuk mendapatkan informasi lebih lanjut tentang produk dan layanan kami</p>
                        <form>
                            <div class="form-group">
                                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="your email">
                                <button class="form-btn-submit">Submit</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section> -->
        <section class="patent">
            <p>Copyright ©2020 Maduku.Store</p>
        </section>
    </footer>
    
</template>

<script>
export default {

}
</script>

<style>
.email-us .form-group{
    width: 70%;
    margin: 0px auto;
}
.email-us .form-group .form-control{
    border: 1px transparent #bbb;
    height: 45px;
    border-radius: 17px;
    background-color: transparent;
}
@media(min-width: 800px) {

}
.footer{
    background-color: #243246;
    color: #bbb;
    padding: 70px 0px;
    margin-top: 100px!important;
}
.footer .about-us, .contact-us, .email-us{
    text-align: center;
}
h4{
    color: #fff;
}
.about-us-one::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
}
.about-us-two::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
}
.about-us-three::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
}
.phone{
    list-style-type: none;
    
}
.patent{
    border-top: 1px solid #bbb;
    background-color: snow;
    text-align: center;
    height: 50px;
    width: 100%!important;
    margin-top: 80px;
    box-shadow: 0 0 16px lightgray;
}
.patent p{
    padding-top: 15px;
    color: grey;
}
.form-control {
    border: 1px solid lightblue;
    width: 120px;
    display: inline-block!important;
    border-radius: 20px 0px 0px 20px!important;
}
.form-btn-submit {
    width: 70px;
    height: 45px;
    border-radius: 0px 20px 20px 0px!important;
    background-color: transparent;
    color: lightblue;
    border: 2px solid lightblue;
}
/* @media (max-width: 768px) {
    .patent {
        width: 100%;
        height: 100%!important;
        justify-content: center;
        text-align: center;
        margin-top: 250px;
    }
}
@media (min-width: 768px) {
    .patent {
        width: 100%;
        height: 100%!important;
        justify-content: center;
        text-align: center;
        margin-top: 140px;
    }
}
@media (max-width: 600px) {
    .patent {
        width: 100%;
        height: 100%!important;
        justify-content: center;
        text-align: center;
        margin-top: 800px;
    }
} */
</style>