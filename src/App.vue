<template>
  <div id="app">
    <HeaderContent/>
    <MainContent/>
    <CardContent/>
   
  </div>
</template>

<script>
import HeaderContent from './components/HeaderContent.vue'
import MainContent from './components/MainContent.vue'
import CardContent from './components/CardContent.vue'

//import axios from 'axios'
export default {
  name: 'App',
  components: {
    HeaderContent,
    MainContent,
    CardContent
    
  },
}
</script>

<style lang="scss">
@import'./styles/general.scss';
</style>
