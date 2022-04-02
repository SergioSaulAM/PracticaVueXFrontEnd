<template>
  <div class="DisponibleDecoraciones">
    <table class="tablaDisponibleDecoraciones">
      <tr>
        <th class="espacioDispPast">Sabor</th>
        <th>Disponibilidad</th>
      </tr>
      <tr>
        <td>Fresas</td>
        <td>Para 20 pasteles</td>
      </tr>
      <tr>
        <td>Chispas de chocolate</td>
        <td>Para 30 pasteles</td>
      </tr>
      <tr>
        <td>Uvas</td>
        <td>Para 15 pasteles</td>
      </tr>
      <tr>
        <td>Duraznos</td>
        <td>Para 19 pasteles</td>
      </tr>
      <tr>
        <td>Kiwi</td>
        <td>Para 15 pasteles</td>
      </tr>
      <tr>
        <td>Mango</td>
        <td>Para 17 pasteles</td>
      </tr>
      <tr>
        <td>Imagen comestible</td>
        <td>Siempre disponible</td>
      </tr>
    </table>
  </div>
</template>


<script>
export default {
    name: 'DisponibleDecoraciones'
}
</script>

<style scoped>
table {
  text-align: left;
}

th {
  width: 250px;
}
</style>