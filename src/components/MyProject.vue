<template>
  <!-- As a link
<nav class="navbar navbar-light bg-light" >
  <div class="container-fluid kutu" >
    <i class="fa-solid fa-droplet icon"></i>
    <a class="navbar-brand " id="Liquet" href="#">Liquet Tracker</a>
     
  </div>
</nav> -->

<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid kutu">
      <i class="fa-solid fa-droplet icon "></i>
    <a class="navbar-brand" href="#" id="Liquet">Liquet Tracker</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">|</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"></a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link" href="#" id="navbarDropdown" role="button"  aria-expanded="false">
            Last Updated: 
          </a>
          
        </li>
        <li class="nav-item">
          <a class="nav-link disabled " >14:42 - 08/09/2000</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100&display=swap');
*{
    margin:0px;
    padding:0px;
}
.kutu{
    background-color:#FFFF;
}
#Liquet{
    color:#551fff;
    font-family:Text,Bold,Regular;
    font-size: 20px;
   
}
.icon{
    color:#551fff;
    padding : 10px;
}
.dropdown{
    opacity: 0.9 ;
}


</style>