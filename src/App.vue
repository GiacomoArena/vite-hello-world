
<script>

import AppTitle from '../src/components/AppTitle.vue'

import Jumbotron from '../src/components/Jumbotron.vue'



export default {
  
  name: 'App',
  components:{
    AppTitle,
    Jumbotron
  }
}
</script>

<template>
  <AppTitle />

  <Jumbotron />

  <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eius molestiae illo nihil dicta neque dolorum porro non quia fugit tempora, ut, deleniti est explicabo minima placeat modi? Quidem, quos vel.</p>


  <AppTitle />
</template>

<style scoped>

</style>