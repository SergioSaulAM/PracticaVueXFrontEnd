<template>
  <Header />
  <div id="pedido">
    <SaboresPasteles />
    <DecoracionesPasteles />
    <CantPersonas />
  </div>
  <Regla />
  <div id="datosContacto">
    <DatosContacto />
    <BotonPedido />
  </div>
  <Info />
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Info from "@/components/Informacion.vue";
import SaboresPasteles from "@/components/SaboresPasteles.vue";
import DecoracionesPasteles from '@/components/DecoracionesPasteles.vue'
import CantPersonas from '@/components/CantPersonas.vue'
import Regla from '@/components/Regla.vue'
import DatosContacto from "@/components/DatosContacto.vue"
import BotonPedido from '@/components/BotonPedido.vue'

export default {
  name: "HomeView",
  components: {
    Header,
    Info,
    SaboresPasteles,
    DecoracionesPasteles,
    CantPersonas,
    Regla,
    DatosContacto,
    BotonPedido,
  },

};
</script>

<style scoped>
#pedido {
  width: 100%;
  display: inline-flex;
  justify-content: space-evenly;
  align-items: center;
}

#datosContacto {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 30px;
}
</style>