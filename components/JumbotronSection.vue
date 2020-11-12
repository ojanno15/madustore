<template>
    <div>
        <div class="sm text-center mt-5 jumbotron-fluid">
            <div class="title">
                <h1 class="title-content">MaduStore.id</h1>
                <h3 class="lead-container">
                    Madu sarang adalah madu Murni yang dipanen beserta sarangnya, jadi kandungan didalamnya 100% terjaga 
                </h3>
                <br>
                <p class="lead-container-hadist">
                    "Madu adalah penyembuh bagi segala penyakit dan Al-Qur'an adalah penyembuh terhadap apa yang ada di dalam dada. Maka bagi kalian terdapat dua penyembuhan; Al-Qur'an dan madu." (HR. Ibnu Majah, 3452 dari hadist Ibnu Mas'ud).
                </p>
                <a class="btn" href="https://wa.me/6282362574353" target="_blank">Beli Sekarang </a>
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
  width: 100%!important;
  display: flex;
  justify-content: space-around;
  background-image: linear-gradient(white,#FBD38D);
  margin: 0px auto;
  padding-top: 60px;
  padding-bottom: 60px;
  /* border-bottom:  2px inset #86d0c1!important; */
  }
@media (max-width: 768px) {
    .font-weight-bold   {
        font-size: 36px;
    }
}
.title-content {
  color: black!important;
}
.btn {
    background-color:#f5cd79;
    border-radius: 10px!important;
    margin-top: 20px;
}
.btn:hover {
    color: grey!important;
}
@media(min-width: 678px){
    .title {
        width: 60%!important;
        text-decoration: none!important;
        color: black!important;
        height: 90vh;
        text-align: center;
        padding-top: 50px!important;
    }
}
.lead-container {
    font-weight: 200;
}
.lead-container-hadist {
    font-style: italic;
}
</style>