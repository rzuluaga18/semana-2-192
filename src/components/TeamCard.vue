<template>
    
      <div class="card text-white bg-dark">
        <div class="d-flex justify-content-center p-2">
        <img :src="member.image" alt="Foto del Integrante">
        </div>
        <div class="card-body">
          <h5 class="card-title"> {{member.nombre}}</h5>
          <p class="card-text">   {{member.descripcion}} </p>
          <h5 class="card-text">   {{member.rol}} </h5>
          <h5 class="card-text text-secondary">  {{ member.codigo }}</h5>
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
