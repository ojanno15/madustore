<template>
    <div>
        <div class="sm text-center jumbotron-fluid">
            <div class="title-container">
                <h3 class="lead-container">
                    Madu Sarang adalah madu murni yang dipanen beserta sarangnya, jadi kandungan didalamnya 100% terjaga 
                </h3>
            </div>
            <div class="hadist">
                <p class="lead-container-hadist">
                    "Madu adalah penyembuh bagi segala penyakit dan Al-Qur'an adalah penyembuh terhadap apa yang ada di dalam dada. Maka bagi kalian terdapat dua penyembuhan; Al-Qur'an dan madu." (HR. Ibnu Majah, 3452 dari hadist Ibnu Mas'ud).
                </p>
            </div>
            <a class="btn button-buy" href="https://wa.me/6281331644952" target="_blank">Beli Sekarang </a>
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
    display: block;
    justify-content: space-around;
    background-image: linear-gradient(#fee996,#fee274);
    margin: 0px auto;
    padding-top: 100px;
    color: white;
    /* padding-bottom: 60px; */
    /* border-bottom:  2px inset #86d0c1!important; */
}
.title-container {
    margin: 0 auto;
    width: 48%;
}
.title-container-content {
    font-weight: 800;
}
.button-buy {
    margin-top: 30px;
    color: #fee274;
    background-color: white;
    font-size: 16px;
    padding: 8px 16px;
}
.btn:hover {
    color: snow!important;
    background-color: #ffdd57;
}
.hadist {
    margin-top: 16px !important;
    width: 50%;
    margin: 0 auto;
}

.lead-container {
    font-weight: 500;
    letter-spacing: 1px;
}
.lead-container-hadist {
    font-style: italic;
}
@media(max-width: 678px){
    .jumbotron-fluid {
        padding-top: 50px !important;
    }
    .title-container {
        width: 100% !important;
        text-decoration: none!important;
        text-align: center;
        padding: 25px 16px;
    }
    .lead-container {
        font-size: 24px;
    }
    .font-weight-bold   {
        font-size: 26px;
    }
    .hadist {
        margin-top: 16px !important;
        padding: 0px 16px;
        width: 100%;
    }
}
</style>