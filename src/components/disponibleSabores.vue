<template>
  <table>
    <tr>
      <td>Nombre:</td>
      <td>Luis Trejo</td>
    </tr>
    <tr>
      <td>Teléfono:</td>
      <td>55 4687 5134</td>
    </tr>
    <tr>
      <td>Correo:</td>
      <td>LuisTrejo98@correo.com</td>
    </tr>
    <tr>
      <td>Descripción:</td>
      <td>Pastel para boda tipo vintage</td>
    </tr>
  </table>
</template>

<script>
export default {
    name: 'disponibleSabores'
};
</script>

<style scoped>
table {
    text-align: left;
    margin: auto;
    margin-bottom: 50px;
    margin-top: 50px;
}

td:nth-child(1) {
    width: 200px;
}
</style>

