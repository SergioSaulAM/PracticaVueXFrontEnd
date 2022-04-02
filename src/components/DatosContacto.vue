<template>
  <div class="datosContacto">
    <h2>Datos de contacto</h2>
    <table>
      <tr>
        <td class="espacio">
          <label for="nombre">Nombre</label>
        </td>
        <td>
          <input
            type="text"
            id="nombre"
            class="centrar"
            name="nombre"
            placeholder="Nombre"
            v-model="enviaNombre"
          />
        </td>
      </tr>

      <tr>
        <td class="espacio">
          <label for="telefono">Teléfono</label>
        </td>
        <td>
          <input
            type="tel"
            name="telefono"
            id="telefono"
            placeholder="Teléfono"
            v-model="enviaTelefono"
          />
        </td>
      </tr>

      <tr>
        <td class="espacio">
          <label for="correo">Correo</label>
        </td>
        <td>
          <input type="email" name="correo" id="correo" placeholder="Correo" v-model="enviaCorreo"/>
        </td>
      </tr>

      <tr>
        <td class="espacio">
          <label for="descripcion">Descripción de pastel</label>
        </td>
        <td>
          <textarea
            name="descripcion"
            id="descripcion"
            cols="21"
            rows="10"
            placeholder="Describe tu pastel"
            v-model="enviaDescripcion"
          ></textarea>
        </td>
      </tr>
    </table>
  </div>
  <BotonDatos @click="enviarDatos()"/>
  <Regla />
  <DatosFinales :nombre="nombre" :telefono="telefono" :correo="correo" :descripcion="descripcion"/>
  
</template>

<script>
import BotonDatos from '@/components/BotonDatos.vue'
import Regla from '@/components/Regla.vue'
import DatosFinales from '@/components/DatosFinales.vue'

export default {
  name: "DatosContacto",
  data() {
    return{
      nombre: null,
      telefono: null,
      correo: null,
      descripcion: null
    };
  },
  methods: {
    enviarDatos() {
        this.nombre = this.enviaNombre;
        this.telefono = this.enviaTelefono;
        this.correo = this.enviaCorreo;
        this.descripcion = this.enviaDescripcion;
    }
  },
  components: {
    BotonDatos,
    Regla,
    DatosFinales
  }
};
</script>


<style scoped>
.datosContacto {
  margin: auto;
}

h2 {
  text-align: center;
}

.espacio {
  width: 120px;
}
</style>