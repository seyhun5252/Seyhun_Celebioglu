<template>
  <div class="card-group">
  <div class="card">
    <div class="card-body">
      <i class="fa-solid fa-droplet icon "></i>
      <h5 class="card-title">Add Tracker</h5>  
    </div>
  </div>
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">Refresh Rate</h5> 
      
            <div class="cards" >
                <a href="#" @onclick="myFunction()">15s</a>
            </div>
            <div class="cards"> 
                <a href="#" @onclick="myFunction2()">30s</a>
            </div>
            <div class="cards" >
                <a href="#" @onclick="myFunction2()">45s</a>
            </div>
            <div class="cards">
                <a href="#" @onclick="myFunction3()">1dk</a>
            </div>
            <div class="cards2">
                <a href="#">25s</a>
            </div>
            <div class="cards2">
                <a href="#">25s</a>
            </div>
      
    </div>
  </div>
  
</div>
</template>

<script>
export default {

},
methods: {
    setInterval(function myFunction(){
        window.location.reload();
    },15000);

    setInterval(function myFunction2(){
        window.location.reload();
    },30000);

    setInterval(function myFunction3(){
        window.location.reload();
    },45000);
    
}
</script>

<style>
a{
    text-decoration:none;
        color: #7549ff;


}
.cards{
    display: inline-block;
    padding-right:40px;
}
.cards2{
    display: inline-block;
    padding-right:40px;
}
.container {
    background-color: white;
    width: 30px;
    height: 30px;
    margin-left:25px;   
    border-radius:10px;
    padding-right: 35px;
    text-align: center;

}
.card{
    border-radius: 50px;
    background-color:#ede8ff;
}
.card .card-title {
    color: #7549ff;
}

</style>