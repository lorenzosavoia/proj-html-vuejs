
<template>
  <div class="container-fluid">
    <Navbar></Navbar>
    <Jumbotron></Jumbotron>
    
  </div>
</template>

<script>
import Navbar from '../components/headerComponents/Navbar.vue'
import Jumbotron from '../components/headerComponents/Jumbotron.vue'
export default {
  name:'Header',
  components: {
      Navbar,
      Jumbotron,
  },
  data(){
      return{
        //   image:"../assets/bg-6.png"
      }
  } 
}

</script>

<style lang='scss' scoped>
 @import "~bootstrap/scss/bootstrap";
 
 .container-fluid{
     
    
 }

</style>