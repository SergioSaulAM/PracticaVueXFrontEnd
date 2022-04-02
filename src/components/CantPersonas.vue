<template>
  <div class="armaPersonas">
    <p class="costoPersonas">Costo por persona: $15</p>
    <p>A partir de 10 personas</p>
    <h3 class="personas">Cantidad de personas</h3>
    <input
      class="personas"
      type="number"
      id="cantPersonas"
      name="cantPersonas"
      min="10"
      placeholder="10"
      value="10"
    />
  </div>
</template>


<script>
export default {
  name: "CantPersonas",
};
</script>


<style scoped>
.armaPersonas {
  display: inline-flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 0;
  padding: 0;
}

p:nth-child(2) {
    margin: 6px 0 6px 0;
    font-size: 1rem;
}

.costoPersonas {
  margin: 6px 0 6px 0;
}

#cantPersonas {
  width: 100px;
}

h3 {
  text-align: center;
  padding: 0;
  margin: 0;
}
</style>