<template>
  <div class="tablaDatos">
    <h2>Datos Registrados</h2>
    <table class="tablaDatosContacto">
      <tr>
        <td class="espacioDatos">Nombre:</td>
        <td class="right">{{ nombre }}</td>
      </tr>
      <tr>
        <td>Teléfono:</td>
        <td class="right">{{ telefono }}</td>
      </tr>
      <tr>
        <td>Correo:</td>
        <td class="right">{{ correo }}</td>
      </tr>
      <tr>
        <td>Descripción:</td>
        <td class="right">{{ descripcion }}</td>
      </tr>
      <tr>
        <td>Sabores:</td>
        <td>
          <ul id="listaSabores" class="list-group">
          </ul>
        </td>
      </tr>
      <tr>
        <td>Decoraciones:</td>
        <td>
          <ul id="listaDecoraciones" class="list-group">
          </ul>
        </td>
      </tr>
      <tr>
        <td>Precio:</td>
        <td>${{$store.state.precioFinal }}.00</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: "DatosFinales",
  props: {
      nombre: null,
      telefono: null,
      correo: null,
      descripcion: null
  }
};
</script>

<style scoped>
td {
  width: 200px;
  text-align: left;
}
.tablaDatosContacto {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

.espacioDatos {
  width: 200px;
}
</style>