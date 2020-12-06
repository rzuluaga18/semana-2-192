<template>

  <div id="app">
    
 

      <!-- INICIO SECCIÓN API -->
        <div class="container-fluid mt-4">
       
           
      <api-seccion>   </api-seccion>      
       
      </div>

      <!-- FIN SECCIÓN API -->
      
   
    
       
    

  </div>

</template>

<script>
import ApiSeccion from './components/ApiSeccion.vue'



export default {
  name: 'App',
  
  components: { 
    ApiSeccion 
    },
  

  data(){
    return{
      
    }
  }
}
</script>

