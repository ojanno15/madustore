<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg fixed-top shadow mb-5 bg-white rounded">
        <a class="navbar-brand pl-4" href="#">MaduStore</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <li class="nav-item"><a class="card-link" href="#" role="button">Madu Satu</a></li>
        <li class="nav-item"><a class="card-link" href="#" role="button">Madu dua</a></li>
        <li class="nav-item"><a class="card-link" href="#" role="button">Madu tiga</a></li>
        
      </div>
    </nav>
   </div>
</template>

<script>
export default {
}
</script>

<style>
container {
  margin: 0;
  padding: 0;
}
body {
  margin: 0px auto;
  width: 100%;
  background-color: #ffe6e6;;
}
.navbar {
  background-color: #effad3!important;
  margin: 0;
  padding: 0;
  height: 4rem;
}
.navbar-brand {
  color: white!important;
}
.card-link {
  color: white!important;
  display: flex;
  justify-content: center;
}
.nav-item {
  text-decoration: none!important;
  display: block;
  padding: 0;
}
</style>