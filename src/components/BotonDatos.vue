<template>
    <button id="BotonDatos" class="Boton_Pedido" @click="$store.commit('holaMundo')">Confirmar Datos</button>
</template>

<script>
export default {
    name: 'BotonDatos'
}
</script>

<style scoped>
.Boton_Pedido {
    background: #DF9475;
    background-image: -webkit-linear-gradient(top, #DF9475, #B96B4B);
    background-image: -moz-linear-gradient(top, #DF9475, #B96B4B);
    background-image: -ms-linear-gradient(top, #DF9475, #B96B4B);
    background-image: -o-linear-gradient(top, #DF9475, #B96B4B);
    background-image: -webkit-gradient(to bottom, #DF9475, #B96B4B);
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    color: #FFFFFF;
    font-family: Brush Script MT;
    font-size: 1.6rem;
    padding: 10px;
    text-decoration: none;
    display: block;
    cursor: pointer;
    width: 170px;
    text-align: center;
    border: none;
    margin-top: 30px;
 }
 
 .Boton_Pedido:hover {
    border: solid #DF9475 1px;
    background: #B96B4B;
    background-image: -webkit-linear-gradient(top, #B96B4B, #D99275);
    background-image: -moz-linear-gradient(top, #B96B4B, #D99275);
    background-image: -ms-linear-gradient(top, #B96B4B, #D99275);
    background-image: -o-linear-gradient(top, #B96B4B, #D99275);
    background-image: -webkit-gradient(to bottom, #B96B4B, #D99275);
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    text-decoration: none;
    border: none;
 }
</style>