<template>
   <div> {{mail}} <br/>{{number}} <br/>{{street}} <br/>{{address}}
   <div>
       {{link}}
   </div>
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
      link:String,
  }
}
</script>
<style>

</style>