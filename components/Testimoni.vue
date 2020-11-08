<template>
    <section class="testimoni" id="testimoni">
        <div class="container" >
            <h3 class="title-product">Apa Kata Mereka Tentang Produk Kami</h3>
            <div class="row">
                <div class="col-md-4 sm-6">
                    <div class="testimoni-card">
                        <img class="rounded-circle" src="../assets/images/boy.png" alt="boy">
                        <p class="customer-comment">
                            Wah, madu nya emang bener bener asli ga diragukan lagi. Walaupun murah tp dapat dipercaya kok. Saya uda beberapa kali membeli dan hasilnya selalu memuaskan. Terimakasih MaduStore. 
                        </p>
                        <div><b>Ramdhan</b><span> - Pengacara</span></div>
                    </div>
                </div>
                <div class="col-md-4 sm-6">
                    <div class="testimoni-card">
                        <img class="rounded-circle" src="../assets/images/girl.png" alt="boy">
                        <p class="customer-comment">
                            Mutu madu disini terjamin, saya membeli madu dengan jenis yang sulit ditemukan di Indonesia. Dan juga pelayanan dari admin ramah dan fast respon.
                        </p>
                        <div><b>Zulaikha</b><span> - Ustadz</span></div>
                    </div>

                </div>
                <div class="col-md-4 sm-6">
                    <div class="testimoni-card">
                        <img class="rounded-circle" src="../assets/images/man.png" alt="boy">
                        <p class="customer-comment">
                            MaduStore memang terbaik, harga terjangkau, mudah, cepat pengirimannya dan juga pelayanannya terbaik. Saya merekomendasikan MaduStore untuk kalian yg ingin mencari madu dengan kualitas, harga, dan pelayanan yg terbaik!
                        </p>
                        <div><b>Makmur</b><span> - Pengusaha</span></div>
                    </div>
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
.testimoni{
    padding-bottom: 80px;
    text-align: center;
    background-color:  #BDE0FE;
    padding-top: 80px;
}
.testimoni-title{
    padding: 20px 0px;
    color: #303030;
}
.title-product::after{
    content: ""; 
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1; 
}
.testimoni-card{
    border: 1px solid lightblue;
    padding: 10px 30px;
    line-height: 30px;
    background: rgba(215, 231, 215, 0.1);  
    box-shadow: 0px 0px 15px lightblue;
    border-radius: 15px;  
    padding: 20px 0px 60px 0px;
    height: 90%;
}
.testimoni-card img{
    padding: 10px 10px;
    border: 2px dashed #e65c00;
    border-radius: 50%;
}
.testimoni p{
    color: rgb(83, 79, 79);
}
 .customer-comment {
     padding: 16px 0px;
 }   
</style>