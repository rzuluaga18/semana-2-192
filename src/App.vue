<template>

  <div id="app">
    <banner-header></banner-header>
 

      <!-- INICIO SECCIÓN API -->
        <div class="container-fluid mt-4">
       
           
      <api-seccion>   </api-seccion>      
       
      </div>

      <!-- FIN SECCIÓN API -->
      
   
   <!-- footer -->
   <footer></footer>
    
       
    

  </div>

</template>

<script>
import ApiSeccion from './components/ApiSeccion.vue'
import BannerHeader from './components/BannerHeader.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'App',
  
  components: { 
    ApiSeccion,
    Footer,
    BannerHeader 
    },

      

  data(){
    return{
      
    }
  }
}
</script>

