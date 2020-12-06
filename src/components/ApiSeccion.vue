<template>

   
   
<!-- mt-5: da un margen arriba en el container -->
  

<div class="row"  >
  
  <div class="col-6" v-for="(item, index) of DataApi" :key="index">     
                    <!-- COLUMNA DE LA IMAGEN DERECHO-->
    <div class="d-flex justify-content-center align-items-center card-body border border-primary bg-secondary text-white"  >
            
           <div class="p-3" >
             <div>
               <!-- NOTA:style="width: 100%; AUTOAJUSTA AL ANCHO -->
               <img v-bind:src="DataApi[index].Poster"  alt="Poster Pelicula" class="rounded">
              </div>
            </div>
            
            <!-- COLUMNA DEL TEXTO DERECHO-->
            <div class="p-3 " >
              <div class="card-body" >
                <h3>{{DataApi[index].Title}}</h3>
                <p class="mt-2">La mejores peliculas sobre comics en un solo lugar, ven y descubre más...</p>
                  <a :href="'https://www.imdb.com/title/' + DataApi[index].imdbID" target="_blank" class="btn btn-outline-light btn-lg">Ver mas</a>
                </div>
          </div>
            

    </div>
  </div>
</div>

    
                     
          
      
     

    
</template>

<script>
import axios from 'axios';

export default {
    name:'ApiSeccion',
    data(){
        return{
            DataApi: [],
        }

    },

    mounted(){
    

    axios
        .get('http://www.omdbapi.com/?apikey=23daade9&s=batman')
        .then(response => {
            (this.DataApi = response.data.Search.slice(0,4)) 
        console.log(this.DataApi)
        });
    }
}
</script>

<style scoped>


</style>