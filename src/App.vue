<template>
  <div id="app">
    <HeaderContent/>
    <MainContent/>
   
  </div>
</template>

<script>
import HeaderContent from './components/HeaderContent.vue'
import MainContent from './components/MainContent.vue'

///import MainContent from './MainContent.vue'
//import axios from 'axios'
export default {
  name: 'App',
  components: {
    HeaderContent,
    MainContent,
    
    //MainContent
  },data(){
    return{
      myArray:[],
    }
  }
}
</script>

<style lang="scss">
@import'./styles/general.scss';
</style>
