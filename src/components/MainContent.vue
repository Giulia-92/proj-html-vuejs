<template>
<section>
<div class="title">
  <h1>Working <h2>process</h2></h1>
  <img  class="svg" src="../assets/img/svg-3.svg" alt="">
  <div class="box">
    <i class="fa-solid fa-cloud"></i>
    <br/>
    <div class="text">
      <h4  class="titoli">First theres an ideas</h4>
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, reprehenderit.
    </div>
  </div>
</div>
 <div class="box1">
    <i class="fa-regular fa-comment"></i>
    <div class="text">
      <h4 class="titoli">Then we talk about</h4>
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, reprehenderit.
    </div>
  </div>
 <div class="box2">
  <i class="fa-solid fa-cloud"></i>
  <div class="text">
      <h4  class="titoli">And we think about</h4>
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, reprehenderit.
    </div>
  </div>
 <div class="box3">
  <i class="fa-regular fa-comment"></i>
  <div class="text">
      <h4  class="titoli">So we draw along</h4>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, reprehenderit.
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

<div class="didascalia">
 <h3> This way,loves:
   a detailed guide through new design</h3>
  <br/>                 
  <h4>I try to give people a differnt way af loking art</h4> 
</div>

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
  margin-left:15%;
  margin-bottom:104px;
  margin-top:-96px;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.box1{ 
  margin-left:35%;
  margin-bottom:8%;
  margin-top:-12%;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.box2{
  margin-left:60%;
  margin-bottom:8%;
  margin-top:-15%;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.box3{
  margin-left:80%;
  margin-bottom:15%;
  margin-top:-15%;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}

.fa-regular{
  color:#F8D12D;
  font-size:45px;
  margin-left:35px;
  margin-top:24px;
}
.fa-solid{
  color: #80465F;
  font-size:45px;
  margin-left:35px;
  margin-top:24px;
}
.img{
 display:inline-flex;
  margin-top:18%;
  width:500px;
  margin-right:-8%;
  margin-left:10%;
}

.sponsor{
  padding-top:5%;
  margin-top:10%;
  padding-left:8%;
  background-color:#C0E1CF;
}
.titoli{
  color: black;
  font-family:'Montserrat', sans-serif;
}
h3{
  font-size:15px;
}
.text{
  font-family:'Montserrat', sans-serif;
  width:300px;
  font-size:15px;
  margin-top:40%;
  margin-left:-10%;
  color: grey;
}
.didascalia{
  border: 1px solid black;
 height: 30px;
 width:83%;
 margin-left: 10%;
 font-family:'Montserrat', sans-serif;
}


</style>
