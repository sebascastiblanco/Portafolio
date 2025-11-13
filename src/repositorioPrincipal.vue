<script setup>
import Perfil from "./components/perfil.vue"
import Foto from "./components/foto.vue"
import Habilidades from "./components/habilidades.vue"
import Experiencia from "./components/experiencia.vue"
import Herramientas from "./components/herramientas.vue"
import Contacto from "./components/contacto.vue"
import Estudios from "./components/estudios.vue"

</script>

<template>
  <div id="contenido_principal">    
      
      <perfil />
      <foto />
      <div id="las_tarjetas">
        <contacto />
        <herramientas />
        <habilidades />
      </div>
      <experiencia />
      <estudios />

  </div>
      
</template>

<style scoped>

#las_tarjetas {

  display: inline-flex;
  flex-direction: row;
  overflow: hidden;
  flex-wrap: wrap;
  align-items: space-between;

}

#contenido_principal {
  display: flex;
  flex-direction: column;
  height: auto;
  width: 100vw;
  justify-content: center;
  align-items: stretch;
  flex-wrap: wrap;
  gap: 2rem;
  background-color: rgb(241, 241, 243);
  overflow-x: hidden; 
  max-width: 1200px;
  margin: 0 auto;
}


</style>
