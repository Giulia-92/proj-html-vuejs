<template>
  <div id="app">
    <HeaderContent/>
  </div>
</template>

<script>
import HeaderContent from './HeaderContent.vue'
//import MainContent from './MainContent.vue'
//import axios from 'axios'
export default {
  name: 'App',
  components: {
    HeaderContent,
    //MainContent
  },data(){
    return{
      myArray:dati,
    }
  }
}
</script>

<style lang="scss">
@import'./styles/general.scss';
</style>
