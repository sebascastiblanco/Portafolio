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
      <contacto />
      <herramientas />
      <habilidades />
      <experiencia />
      <estudios />

  </div>
      
</template>

<style scoped>

#contenido_principal {
  display: flex;
  flex-direction: column;
  height: auto;
  width: 80vw;
  justify-content: center;
  align-items: stretch;
  flex-wrap: wrap;
  gap: 5rem;
  background-color: rgb(221, 221, 231);
}


</style>
