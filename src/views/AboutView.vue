<template>
  <Header />
  <h1>Disponibilidad</h1>
  <div class="disponibilidad">
    <DisponiblePasteles />
    <DisponibleDecoraciones />
  </div>
  <Regla />
  <h1>Pedidos</h1>
  <disponibleSabores />
  <disponibleSabores />
  <Informacion />
</template>

<script>
import Header from "@/components/Header.vue";
import disponibleSabores from "@/components/disponibleSabores.vue";
import Regla from "@/components/Regla.vue";
import DisponiblePasteles from "@/components/DisponiblePasteles.vue";
import DisponibleDecoraciones from "@/components/DisponibleDecoraciones.vue";
import Informacion from '@/components/Informacion.vue'

export default {
  components: {
    Header,
    disponibleSabores,
    Regla,
    DisponiblePasteles,
    DisponibleDecoraciones,
    Informacion
  },
};
</script>

<style scoped>
.disponibilidad {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
</style>
