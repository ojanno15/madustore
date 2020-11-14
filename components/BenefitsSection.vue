<template>
  <div class="benefits" id="benefits">
        <div class="benefits-section">
            <h3 class="benefits-title">
                Manfaat Madu
            </h3>
            <p class="benefits-content">
                Terdapat 1001 manfaat dalam Madu Sarang juga Kaya akan berbagai macam vitamin, mineral, dan protein dalam sarang madu. 
            </p>
            <p class="benefits-content">
                Sarang Madu juga dapat membuat awet muda, menyuburkan masa kehamilan, penurun berat badan alami, menurunkan kolestrol jahat, melindungi fungsi hati, mempercepat penyembuhan luka, menjaga kesehatan mulut, mengobati peradangan akibat bakteri atau virus, dan juga mampu untuk meningkatkan sistem kekebalan tubuh. 
            </p>
            <p class="benefits-content">
                Lebih dari ribuan tahun yang lalu, Allah SWT mewahyukan kepada Nabi Muhammad SAW bahwa madu dapat menyembuhkan manusia dari berbagai macam penyakit. 
            </p>
            <p class="benefits-content">
                Madu digambarkan di dalam Al-Quran sebagai sumber penyembuhan: Quran Surat An-Nahl Ayat 68-69 Dalam ayat lainnya, madu juga digambarkan sebagai salah satu makanan yang ada di surga: (Quran Surat Muhammad Ayat 15).
            </p>
            <p class="benefits-button-buy">
                CASH ON DELIVERY (COD) JUGA BISA, JANGAN DIBAYAR SAMPAI BARANG TIBA!
            </p>
            <div class="animated bounce">
                <img src="../assets/images/Downpict.png" class="img-bottom-cursor" alt="">
            </div>
            <div class="benefits-button">
                <a class="btn benefits-button" id="booking" href="https://wa.me/6281331644952" target="_blank">Pesan Sekarang</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.benefits-section {
    width: 700px;
    margin: 0 auto;
}
.benefits {
    width: 70%;
    margin-left: 15%;
    text-align: center;
    padding-top: 70px;
}
.benefits-title,
.benefits-button-buy,
.benefits-button {
    text-align: center;
    letter-spacing: 2px;
}
.benefits-content {
    font-weight: 300;
    font-size: 18px;
    margin-top: 50px;
    letter-spacing: 1px;
}
.benefits-button-buy {
    font-style: oblique;
    font-size: 18px;
    font-weight: 800;
    margin-top: 40px;
}
.benefits-button {
    padding-top: -20px;
}
.benefits-title::after {
    content: "";
    display: block;
    width: 100px;
    height: 3px;
    margin: 24px auto;
    background: #fee274;
}
.img-bottom-cursor {
    width: 50px!important;
}
.animated {
  -webkit-animation-duration: .5s;
  animation-duration: .5s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-timing-function: linear;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
  -webkit-animation-iteration-count: infinite;
}

@media(max-width: 678px) {
    .benefits-section {
        width: 100%;
        padding: 0px 16px;
    }
    .benefits {
        margin-left: 0px !important;
        width: 100%;
    }
}
@-webkit-keyframes bounce {
  0%, 100% {
    -webkit-transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(-5px);
  }
}
@keyframes bounce {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-5px);
  }
}
.bounce {
  -webkit-animation-name: bounce;
  animation-name: bounce;
}
/* .benefits {
    text-align: center!important;
    width: 100%important;
    height: 500px;
    padding-top: 20px;
}
.benefits-title::after {
    content: "";
    display: block;
    width: 100px;
    height: 2px;
    margin: 24px auto;
    background: gray;
}
.benefits-content {
    width: 80%!important;
    margin: 0px auto;
    padding-top: 60px;
    text-align: justify;
    font-weight: 800;
    font-size: 18px;
}
.benefits-button-buy {
    text-align: center;
    font-weight: 800;
    font-size: 18px;
    font-style: oblique;
} */
/* @media(max-width: 600px) {
    .benefits {
        margin-bottom: 700px!important;
    }
    .benefits-button-buy {
        width: 100%!important;
        padding: 50px;
    }
    .benefits-content {
        width: 100%!important;
        height: 100%!important;
        text-align: justify;
        padding: 50px;
    }
} */
/* @media(max-width: 768px) {
    .benefits {
        margin-bottom: 280px;
    }
    .benefits-content {
        width: 100%!important;
        height: 100%!important;
        text-align: justify;
        padding: 50px;
    }
} */
/* @media(min-width: 768px) {
    .benefits-content {
        width: 100%!important;
        height: 100%!important;
        text-align: justify;
        padding: 50px;
    }
    .benefits {
        margin-bottom: 140px;
    }
} */
</style>