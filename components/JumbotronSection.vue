<template>
    <div>
        <div class="sm text-center mt-5 jumbotron-fluid">
            <!-- <img src="../assets/images/madu3d.webp" alt="" class="card-img image-jumbotron card-columns"> -->
            <div class="title">
                <h4 class="title-content display-8">Selamat Datang Di Madu Store</h4>
                <p class="lead container">
                    This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.
                </p>
                <a class="btn text-light" href="https://wa.me/6282362574353" target="_blank">Beli Sekarang </a>
            </div>
        </div>      
    </div>
</template>

<script>
export default {
}
</script>

<style>
body {
    font-family: Nunito,serif!important;
}
.jumbotron-fluid {
  margin: 0;
  border: 0px;
  border-radius: 0;
  width: 100%!important;
  background-color: white;
}
@media (max-width: 768px) {
    .font-weight-bold   {
        font-size: 36px;
    }
}
.title {
  width: 100%!important;
  padding-top: 240px;
  text-decoration: none!important;
  color: black!important;
  height: 90vh;
  background-color: #BDE0FE;
}
.title-content {
  color: black!important;
}
.btn {
    background-color: #ECBC68;
    border-radius: 10px!important;
}
</style>