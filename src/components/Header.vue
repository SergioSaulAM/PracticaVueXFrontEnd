<template>
  <div class="fondo">
    <div class="fondocolor">
      <div class="header">
        <div class="nav">
          <img
            class="NombrePasteleria"
            src="https://i.ibb.co/1rXJvLM/Nombre-logo.png"
            alt="Nombre Pastelería"
          />
          <ul>
            <li>Acerca de Nosotros</li>
            <li>Historia</li>
            <li>
              <router-link to="/">Realizar pedido</router-link>
            </li>
            <li>
              <router-link to="/about">Pedidos pendietes</router-link>
            </li>
          </ul>
        </div>
      </div>
      <img
        class="logoFondo"
        src="https://i.ibb.co/WzNFztX/Logo.png"
        alt="Logo Pastelería"
      />
    </div>
  </div>
</template>

<script>
export default {
    name: 'Header'
};
</script>

<style scoped>
.nav {
  background-color: rgb(255, 178, 166, 0);
  display: flex;
  justify-content: space-between;
  align-items: center;
  display: absolute;
  top: 0;
  font-size: 1.6rem;
}

.header {
  position: absolute;
  top: 0;
  width: 100%;
}

section {
  grid-area: section;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.NombrePasteleria {
  width: 200px;
  padding-top: 20px;
  padding-left: 80px;
}

.fondo {
  background-image: url("https://images.unsplash.com/photo-1542826438-bd32f43d626f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1592&q=80");
  background-size: 100% 100vh;
  background-repeat: no-repeat;
  background-position-y: -80px;
  margin: 0;
}

.logoFondo {
  width: 300px;
  height: 300px;
}

.fondocolor {
  width: 100%;
  height: 70vh;
  background-color: rgb(255, 180, 168, 0.7);
  display: flex;
  justify-content: center;
  align-items: center;
}

ul {
    list-style: none;
    width: 40%;
    padding: 0;
    display: flex;
    justify-content: space-evenly;
}

.menu {
    margin: auto;
    text-align: left;
}

router-link {
  color: #a0664e;
  text-decoration: none;
}
</style>