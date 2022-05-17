<template>
<section>
<div class="title">
  <h1>Working <h2>process</h2></h1>
  <img  class="svg" src="../assets/img/svg-3.svg" alt="">
  <div class="box">
    <i class="fa-solid fa-cloud"></i>
  </div>
</div>

<div>
 <img src="../assets/img/h-2-background-1.jpg" alt="">
 <div class="contact">
 <h3>Want to work with us?Send us a <h2>message</h2></h3>
 <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Rerum enim tempore aut dolorem fugiat ex?</p>
 <button class="btn2">CONTACT</button>
</div>
</div>
<section>
<img src="../assets/img/h-2-blog-img-1.jpg" class="img" alt="...">

<img src="../assets/img/h-2-blog-img-2.jpg" class="img" alt="...">

<img src="../assets/img/h-2-blog-img-3.jpg" class="img" alt="...">

</section>
<section class="sponsor">
  <img src="../assets/img/logo-sidearea-1.png" alt="">
</section>
</section>

    
</template>

<script>
export default {
  name: 'MainContent',
  data(){
    return{
    }
  }
} 
</script>
<style>
h1{
  text-align: center; 
}
.contact{
  text-align: center;
  margin-top:-20%;
}
.btn2{
  text-align:center;
   font-family:'Montserrat', sans-serif;
  background-color:#D8F0E3;
  border:1px solid #D8F0E3;
  height:40px;
  width:150px;
 
}
.title{
  margin-top:50px;
}
.svg{
  margin-top:90px;
  margin-left:300px;
}
.box{
  height:20px;
  width:20px;
  border: 1px solid black;
}
.img{
  display:inline-flex;
  margin-top:20%;
  width:418px;
  margin-right:-8%;
  margin-left:10%;
}
.sponsor{
  padding-top:8%;
  margin-top:15%;
  background-color:#C0E1CF;;
}
.text{
  font-size:15px;
}


</style>
