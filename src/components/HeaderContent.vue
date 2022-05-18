<template>
    
<header>
  <img class="logo" src="../assets/img/logo-sidearea-1-1.png" alt="">

  <ul> 
  <li class="menu">
    <a href="#"><LinkContent v-for="(item) in links" :key="item" :link="item.link" /> </a>
    </li>
  </ul>
  <div class="imenu">
      <img src="../assets/img/svg-1.svg" alt="">
   </div>
  <div class="top1">
    <h1>Devotion that never <h2>ends</h2></h1>
   <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.Adipisci, rem esse! Quaerat modi deserunt ullam id et soluta doloribus, qui corrupti impedit at, minima hic saepe.</p>
   <button class="btn1">READ MORE</button>
    </div>
    <div class="picture">
    <img src="../assets/img/h-2-slider-img-15.png" alt="figura1">
    <img src="../assets/img/h-2-slider-img-16.png" alt="figura2">
    </div>
    <img class="s" src="../assets/img/h-2-slider-img-17.png" alt="">
    <img class="s1" src="../assets/img/h-2-slider-img-13.png" alt="">
    <img class="s2" src="../assets/img/h-2-slider-img-12.png" alt="">
    <img class="s3" src="../assets/img/h-2-slider-img-14.png" alt="">
    <img class="s4" src="../assets/img/short-slider-rev-1-img-6.png" alt="">
  
  <div class="icone">
  <img src="../assets/img/svg-6.svg" alt="">
  <img src="../assets/img/svg-7.svg" alt="">
  </div>
  <section class="jumbo">
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
import LinkContent from './LinkContent.vue'
export default {
  name: 'HeaderContent',
  components:{
      LinkContent
      },
  data(){
    return{
      links:[
      {
        "link":"Home"
      },
      {
        "link":"Porfolio"
      },
      {
        "link":"Blog"
      },
      {
        "link":"Shop"
      },
      {
        "link":"Pages"
      },
      {
        "link":"Porfolio"
      },
      ]
    }
  }
}

    
</script>
<style>

.logo{
  margin-top:-24px;
}
ul{
  display:inline-flex;
  justify-content: flex-end;
  list-style-type:none;
  color: black;
  margin-left: 190px;
  margin-right:-110px;
}

a{
  color: black;
  text-decoration: none
}
a:hover{
  text-decoration: underline #F3d0c7 4px;
}
.imenu{
  margin-left:90%;
  margin-top:-42px;
}
 

.grid{
  height:15px;
  width:20px;
  margin-top:12px;
  margin-right:20px;
}
.top1{
  font-size:20px;
  color: black;
  font-family:'Montserrat', sans-serif;
  margin-left:25%;
  margin-top:8%;
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
.icone{
  height:35px;
  width:35px;
  margin-left:97%;
  position:absolute;
  margin-top:60px;
  position: fixed;
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
.btn1:hover{
  background-color:#F3D0C7 ;
}

.picture{
  margin-right:100px;
  margin-top:-15%;
  display: flex;
  justify-content: flex-end;
}
.img-fluid{
width:635px;
display:inline-flex;
}
.s{
  height:129px;
  width:97px;
  margin-left:90%;
  margin-top:-162px;
}
.s1{
  margin-left:48%;
  margin-top:-10%;
}
.s2{
  margin-top:-30%;
  
}
.s3{
  margin-top:-55%;
  margin-left:88%;
}
.s4{
  margin-top:-50%;
  margin-left:55%;
}

</style>