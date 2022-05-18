<template>
   <div> {{mail}} <br/>{{number}} <br/>{{street}} <br/>{{address}}
  
       </div> 
       
</template>


<script>
export default {
  name: 'CardContent',
  props:{
      mail:String,
      address:String,
      number:Number,
      street:String,
     
  }
}
</script>
<style>

</style>