<template>
<section>
<div class="title">
  <h1>Working <h2>process</h2></h1>
  <img  class="svg" src="../assets/img/svg-3.svg" alt="">
  <div class="box">
    <i class="fa-brands fa-medapps"></i>
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
  <i class= "fa-solid fa-cloud"></i>
  <div class="text">
      <h4  class="titoli">And we think about</h4>
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, reprehenderit.
    </div>
  </div>
 <div class="box3">
  <i class="fa-solid fa-marker"></i>
  <div class="text">
      <h4  class="titoli">So we draw along</h4>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, reprehenderit.
    </div>
  </div>


<div class="sfondo">
 <img src="../assets/img/h-2-background-1.jpg" alt="">
 </div>
 <div class="contact">
 <h3>Want to work with us?Send us a <h2>message</h2></h3>
 <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Rerum enim tempore aut dolorem fugiat ex?</p>
 <button class="btn2">CONTACT</button>
</div>



<section>
 
  <div class="date">07</div>
<ul class="lista">
    <li ><img src="../assets/img/h-2-blog-img-1.jpg" class="img" alt="..."><h5> This way,loves:
   a detailed guide through new design</h5><h6> By Emily Fields</h6></li> 
   <div class="age2">May ' 19</div>
    <li><div class="date1">07</div><img src="../assets/img/h-2-blog-img-2.jpg" class="img" alt="..."><h5> I try to give people a different way of looking art</h5><h6>By Emily Fields</h6></li>
    <div class="age1">May ' 19</div>
    <li><div class="date2">07</div><img src="../assets/img/h-2-blog-img-3.jpg" class="img" alt="..."><h5> Introduce Richard Laperrière of those amazing features</h5><h6>By Emily Fields</h6></li>
  </ul>
 <div class="age">May ' 19</div>
</section>
<section class="sponsor">
  <img src="../assets/img/logo-sidearea-1.png" alt="">
 
    <div class="contatto"><CardContent v-for="(item) in contacts" :key="item" :mail="item.mail" :address="item.address" :number="item.number" :street="item.street"/> </div>
   <div>

     <div class="social"> Stay in touch with us
            <img src="../assets/img/footer-twitter.png" alt="" > 
            <img src="../assets/img/footer-pinterest.png" alt="" > 
            <img src="../assets/img/footer-facebook.png" alt="" > 
      </div>

  </div>
</section>
</section>

    
</template>

<script>
import CardContent from './CardContent.vue'
export default {
 name: 'MainContent',
  components:{
   CardContent
  },
  data(){
    return{
      contacts:[
    {
        "number":"+44645321789",
        "mail": "maree.qode@gmail.com",
        "address":"1040 Brussels,Belgium",
        "street":"Avenue d'Auderghem 10",
        
    },
     {
        "number": "+44645321789",
        "mail": "maree.qode@gmail.com",
        "address":"1040 Brussels,Belgium",
        "street":"Avenue d'Auderghem 10",
         
    },
     {
        "number": "+44645321789",
        "mail": "maree.qode@gmail.com",
        "address":"1040 Brussels,Belgium",
        "street":"Avenue d'Auderghem 10",
         
    },
    ]
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
  margin-left:13%;
  margin-bottom:104px;
  margin-top:-103px;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.box1{ 
  margin-left:35%;
  margin-bottom:8%;
  margin-top:-13%;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.box2{
  margin-left:54%;
  margin-bottom:10%;
  margin-top:-11%;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.box3{
  margin-left:70%;
  margin-bottom:15%;
  margin-top:-16%;
  height:105px;
  width:130px;
  background-color:#FAF7F1;
  border-radius:50%;
}
.fa-brands{
  color:#C0E1CF;
  font-size:45px;
  margin-left:47px;
  margin-top:24px;
}
.fa-regular{
  color:#F8D12D;
  font-size:45px;
  margin-left:35px;
  margin-top:34px;
}
.fa-solid{
  color: #80465F;
  font-size:45px;
  margin-left:35px;
  margin-top:24px;
}
.img{
  display:inline-flex;
  width:500px;
  margin-left:8%;
  margin-bottom:63px;
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
.sfondo{
 overflow-x: hidden;
 margin-bottom: 89px;
}
.lista{
  list-style-type:none;
  display: flex;
  margin-top:10%;
  margin-left:4%;
  margin-right:3%;
}
.date{
  margin-left:10%;
  margin-top:-10px;
  height:58px;
  width:56px;
  background-color:#C0E1CF;
  position: absolute;
  color: black;
  font-family:'Lobster', cursive;
  text-align:center;
  font-size:35px;
}
.date1{
   margin-left:5%;
  margin-top:-11px;
  height:58px;
  width:56px;
  background-color:#C0E1CF;
  position: absolute;
  color: black;
  font-family:'Lobster', cursive;
  text-align:center;
  font-size:35px;
}
.date2{
 margin-left:5%;
  margin-top:-10px;
  height:58px;
  width:56px;
  background-color:#C0E1CF;
  position: absolute;
  color: black;
  font-family:'Lobster', cursive;
  text-align:center;
  font-size:35px; 
}
.age{
  position: absolute;
  border: 1px solid #F3D0C7;
  height:44px;
  width:57px;
  margin-left:190px;
  margin-top:-25%;
  font-size: 17px;
  padding-top:5px;
   font-family:'Lobster', cursive;
}
.age1{
  position: absolute;
  border: 1px solid #F3D0C7;
  height:44px;
  width:57px;
  margin-left:32.7%;
  margin-top:46px;
  font-size:17px;
  padding-top:5px;
  font-family:'Lobster', cursive;
  background-color:#F5D8CA;
}
.age2{
   position: absolute;
  border: 1px solid #F3D0C7;
  height:44px;
  width:57px;
  margin-left:59%;
  margin-top:47px;
  font-size:15px;
  padding-top:5px;
  font-family:'Lobster', cursive;
  background-color:#F5D8CA;
}
h5{
  font-family:'Montserrat', sans-serif;
  margin-left:10%;
}
h6{
font-family:'Smooch', cursive;
margin-left:10%;
}

.contatto{
  display: inline-flex;
  gap: 109px;
  margin-top:-7%;
  margin-left:10%;
  margin-bottom:36px;
  font-size:20px;
  font-family:'Montserrat', sans-serif;
}
.social{
  margin-left:80%;
  margin-top:-37px;
  font-family:'Montserrat', sans-serif;
  font-size:20px;
}



</style>
