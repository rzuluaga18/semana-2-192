<template>
    
      <div class="card text-white bg-dark">
        <div class="d-flex justify-content-center p-2">
        <img :src="member.Imagen" alt="Foto del Integrante">
        </div>
        <div class="card-body">
          <h5 class="card-title"> {{member.Nombre}}</h5>
          <p class="card-text">   {{member.Descripcion}} </p>
          
        </div>
        <div class="card-footer">
          <small class="text-muted">Grupo 192</small>
        </div>
      </div>
    
  
</template>

<script>
export default {
  name: "TeamCard",
  props: ["member"],
};
</script>

<style scoped>

</style>
