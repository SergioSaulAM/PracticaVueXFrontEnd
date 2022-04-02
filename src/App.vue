<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->

  <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;700&display=swap" rel="stylesheet">
  <router-view />
</template>

<style>

body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Dancing Script", cursive;
  font-size: 26px;
  color: #804c36;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
text-align: center;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
