<template>
    
<header>
  <img class="logo" src="../assets/img/logo-sidearea-1-1.png" alt="">
  <div class="top1">
    <h1>Devotion that never <h2>ends</h2></h1>
   <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.Adipisci, rem esse! Quaerat modi deserunt ullam id et soluta doloribus, qui corrupti impedit at, minima hic saepe.</p>
   <button class="btn1">READ MORE</button>
    </div>
    <div class="picture">
    <img src="../assets/img/h-2-slider-img-15.png" alt="figura1">
    <img src="../assets/img/h-2-slider-img-16.png" alt="figura2">
    </div>
  
  <section>
   <img src="../assets/img/h-2-port-img-1.jpg" class="img-fluid" alt="...">
   <img src="../assets/img/h-2-port-img-2.jpg" class="img-fluid" alt="...">
   <img src="../assets/img/h-2-port-img-3.jpg" class="img-fluid" alt="...">
   <img src="../assets/img/h-2-port-img-4.jpg" class="img-fluid" alt="...">
   <img src="../assets/img/h-2-port-img-5.jpg" class="img-fluid" alt="...">
   <img src="../assets/img/h-2-port-img-6.jpg" class="img-fluid" alt="...">
  </section>
   
</header>
    
</template>
<script>
export default {
  name: 'HeaderContent',
  data(){
    return{
    
    }
  }
}

    
</script>
<style>
.top1{
  font-size:20px;
  color: black;
  font-family:'Montserrat', sans-serif;
  margin-left:25%;
  margin-top:15%;
  margin-right:50%;
}
p{
  color: #A6A6A6;
  font-size:13px;
}
h2{
  color:black;
 font-family: 'Lobster', cursive;
}
.btn1{
  color: black;
  font-size:10px;
  width:120px;
  height:40px;
  border:2px solid #E1C0B0;
  font-family:'Montserrat', sans-serif;
  background-color:#FFFFFF;
}

.picture{
  margin-top:-15%;
  display: flex;
  justify-content: flex-end;
}
.img-fluid{

width:550px;
display:inline-flex;

}

</style>