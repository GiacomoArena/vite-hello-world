
<script>
export default {
  name: 'Jumbotron',

  DataTransfer(){
    return{
      image: 'ondaa.jpg'
    }
  },

  methods:{
    getImage(img){
      return new URL(`../assets/${img}`, import.meta.url).href
    }
  }

}
</script>

<template>

  <img :src="getImage(image)" alt=" immagine dinamica">
  
</template>

<style>

</style>