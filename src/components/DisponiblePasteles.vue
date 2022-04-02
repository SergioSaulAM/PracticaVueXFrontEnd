<template>
  <div class="DisponiblePasteles">
    <table class="tablaDisponiblePasteles">
      <tr>
        <th>Sabor</th>
        <th>Disponibilidad</th>
      </tr>
      <tr>
        <td>Chocolate</td>
        <td>7 pasteles</td>
      </tr>
      <tr>
        <td>Nuez</td>
        <td>9 pasteles</td>
      </tr>
      <tr>
        <td>Cajeta</td>
        <td>8 pasteles</td>
      </tr>
      <tr>
        <td>Café</td>
        <td>5 pasteles</td>
      </tr>
      <tr>
        <td>Arroz con leche</td>
        <td>6 pasteles</td>
      </tr>
      <tr>
        <td>Queso con zarzamora</td>
        <td>3 pasteles</td>
      </tr>
      <tr>
        <td>3 leches</td>
        <td>4 pasteles</td>
      </tr>
    </table>
  </div>
</template>


<script>
export default {
    name: 'DisponiblePasteles'
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