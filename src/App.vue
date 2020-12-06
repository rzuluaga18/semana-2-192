<template>

  <div id="app">
    <banner-header></banner-header>
 

      <!-- INICIO SECCIÓN API -->
        <div id="news" class="container-fluid mt-4">
       
           
      <api-seccion>   </api-seccion>      
       
      </div>

      <!-- FIN SECCIÓN API -->

<!-- integrantes  -->
    <div id="team" class="container-fluid">
    <div class="row justify-content-center mb-5">
      <div class="col mt-5" v-for="(item,index) of team" :key="index">
        <team-card v-bind:member="item"></team-card>
      </div>
   </div>
  </div>  
  <!-- fin integrantes  -->

   
   <!-- footer -->
  <Footer></Footer>
    
       
    

  </div>

</template>

<script>
import ApiSeccion from './components/ApiSeccion.vue'
import BannerHeader from './components/BannerHeader.vue'
import Footer from './components/Footer.vue'
import TeamCard from './components/TeamCard.vue'



export default {
  name: 'App',
  
  components: { 
    ApiSeccion,
    Footer,
    TeamCard, 
    BannerHeader, 

    },

      

  data(){
    return{
            team: [
        {
          codigo: 1,
          Nombre: 'Luis Carlos Arrieta Sierra',
          Descripcion: 'Estudiante de Ingeniería de sistemas en la Universidad Nacional, 31 años. Pasatiempo es jugar tenis. ',
          
          Imagen: "https://lh3.googleusercontent.com/-xzP3h9cTaL0/WeOwvJ1_eaI/AAAAAAAAAxQ/zz6xnDsZPrASd19sZWLswGh5TFHO2nnygCEwYBhgLKtMDAL1Ocqz-Moo9m9KKmwuaZF2YKW93IzhwK1FS4bNRbGBIRfdLU26qDU1tlm5l2E_v8F0rONYtcFsoakothwyr3VP59Sbx5PxvPLnRbKU8K6ByVt78eEBOyMhezVNlXvOEd5r15OXAoYBzynLlB6lObxgJoqkPc0XwM_pzghYpgZ1X5tg6IcLcdQCQ89QvHQPaWEWG1WTUgx5o7QqvTUSqekjRV5reM9464-kJZuZc3ExwSOfGx-GQGtpp60ATzdfZirp4UaRNYd7id3wCGFB81XhAcy28xstTnIboNEqt1pOEUy9HrPZijr3R-mGDRnoZ9DWykOUvQvSvLeQ3a1gEQ04lS-s1AMmqHL1IbSG-tUAjpro5D-WswxU6A1nEkWaIT1uIs2Gwg61qoM0TUem_UJorIS96RBDabHFSy2isolSriX62Nr297QVPbWfN_c4UmQHsZmToG-i_H_KPAN1fxzYRe6jpY7588TfOOi6uScRaaYA4e7usizJFRGPlvYUw-OAi8Me3ZMVP5WnR-blx4ya60rQhw8GYIz-kNPyJOicl1ihGB-NoTczP_Exp0llFPe6t-VYpd5qOGsIH31TKIOYUr6JGwE5ZSwlrCBPDY5eQ-0IwmOuw_gU/w140-h140-p/ppee.png",
          }, 
          {
            codigo: 2,
            Nombre: 'Angie Sofía Benito Suárez',
            Descripcion: 'Estudiante de matemáticas en la Universidad Distrital, 22 años. Pasatiempo es ver series y/o películas.',
            
            Imagen: require('./assets/Angie.jpg'),
            }, 
            {
            codigo: 3,
            Nombre: 'Ramiro Andrés Zuluaga Parra',
            Descripcion: 'Ingenierío electrónico de la Universidad del Quindio, 35 años. Pasatiempo es jugar fútbol.',
            
            Imagen: require('./assets/Ramiro.jpg'),
            },
            {codigo: 4,
            Nombre: 'Cristiam David Bustos Fuentes',
            Descripcion: 'Estudiante de Ingeniería Industrial en la Universidad Del Norte, 21 años. Pasatiempo es jugar videojuegos y leer.',
            
            Imagen: require('./assets/Cristiam.jpeg'),
            }
            ]
    }
  }
}
</script>

