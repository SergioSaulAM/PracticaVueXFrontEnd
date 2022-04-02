<template>
  <footer>
    <h2 class="estiloPadding">Visítanos</h2>
    <h5 class="estiloPadding">
      Av. Nueva Aventura #73 Col. La Pradera del Sol
    </h5>
    <h5 class="estiloPadding">Horario de atención: 10 hrs - 20 hrs</h5>
  </footer>
</template>

<script>
export default {
  name: "Info",
};
</script>

<style scoped>
.estiloPadding {
  padding: 10px 0 10px 0;
  margin: 0;
}

footer {
    background-color: #FFB2A6;
    grid-area: footer;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 50px;
    margin: 0;
}
</style>