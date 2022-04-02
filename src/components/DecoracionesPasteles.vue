<template>
  <div class="armarDecoraciones">
                <h3>Decoraciones</h3>
                <table>
                    <tr>
                        <td> <input type="checkbox" name="Fresas" id="Fresas"> </td>
                        <td class="armaDecoraciones">Fresas</td>
                        <td>$30</td>
                    </tr>
                    <tr>
                        <td><input type="checkbox" name="chocolate" id="chocolate" value="Chispas de chocolate"></td>
                        <td class="armaDecoraciones">Chispas de chocolate</td>
                        <td>$30</td>
                    </tr>
                    <tr>
                        <td><input type="checkbox" name="uvas" id="uvas" value="Uvas"></td>
                        <td class="armaDecoraciones">Uvas</td>
                        <td>$30</td>
                    </tr>
                    <tr>
                        <td><input type="checkbox" name="duraznos" id="duraznos" value="Duraznos"></td>
                        <td class="armaDecoraciones">Duraznos</td>
                        <td>$30</td>
                    </tr>
                    <tr>
                        <td><input type="checkbox" name="kiwi" id="kiwi" value="Kiwi"></td>
                        <td class="armaDecoraciones">Kiwi</td>
                        <td>$30</td>
                    </tr>
                    <tr>
                        <td><input type="checkbox" name="mango" id="mango" value="Mango"></td>
                        <td class="armaDecoraciones">Mango</td>
                        <td>$30</td>
                    </tr>
                    <tr>
                        <td><input type="checkbox" name="imagen" id="imagne" value="Imagen comestible"></td>
                        <td class="armaDecoraciones">Imagen comestible</td>
                        <td>$30</td>
                    </tr>
                </table>
            </div>
</template>

<script>
export default {
  name: "DecoracionesPasteles",
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

.armaDecoraciones {
    width: 300px;
    padding-left: 20px;
}

table {
    text-align: left;
}
</style>