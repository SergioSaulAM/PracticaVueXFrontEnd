<template>
  <div class="armarSabores">
    <h3>Sabores</h3>
    <table>
      <tr>
        <td><input type="checkbox" name="chocolate" id="chocolate"/></td>
        <td class="armaSabor"><label for="chocolate">Chocolate</label></td>
        <td>$100</td>
      </tr>
      <tr>
        <td><input type="checkbox" name="nuez" id="nuez" value="Nuez"/></td>
        <td class="armaSabor"><label for="nuez">Nuez</label></td>
        <td>$100</td>
      </tr>
      <tr>
        <td><input type="checkbox" name="cajeta" id="cajeta" value="Cajeta"/></td>
        <td class="armaSabor"><label for="cajeta">Cajeta</label></td>
        <td>$100</td>
      </tr>
      <tr>
        <td><input type="checkbox" name="cafe" id="cafe" value="Café"/></td>
        <td class="armaSabor"><label for="cafe">Café</label></td>
        <td>$100</td>
      </tr>
      <tr>
        <td><input type="checkbox" name="arroz" id="arroz" value="Arroz con leche"/></td>
        <td class="armaSabor"><label for="arroz">Arroz con leche</label></td>
        <td>$100</td>
      </tr>
      <tr>
        <td><input type="checkbox" name="queso" id="queso" value="Queso con Zarzamora"/></td>
        <td class="armaSabor"><label for="queso">Queso con zarzamora</label></td>
        <td>$100</td>
      </tr>
      <tr>
        <td><input type="checkbox" name="leches" id="leches" value="3 leches"/></td>
        <td class="armaSabor"><label for="leches">3 leches</label></td>
        <td>$100</td>
      </tr>
    </table>
  </div>
  
</template>

<script>

export default {
  name: "SaboresPasteles"
};
</script>

<style scoped>
h3 {
  margin: 20px 0;
}

div {
  margin: 20px 0 40px 0;
  display: inline-flex;
  flex-direction: column;
  align-items: center;
}

.armaSabor {
    width: 300px;
    padding-left: 20px;
}

table {
    text-align: left;
}
</style>