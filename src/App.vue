<template>

  <div id="app">
    
 

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
import Footer from './components/Footer.vue'



export default {
  name: 'App',
  
  components: { 
    ApiSeccion,
    Footer 
    },

      

  data(){
    return{
      
    }
  }
}
</script>

