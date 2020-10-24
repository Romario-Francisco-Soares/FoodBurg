<template>
  <div id="App">
  <!--<foodburgcomponente /> -->
  <cabeca/>
  <especialidades/>
  <ambiente/>
  <bebidas/>
  <preco/>
  </div>
</template>

<script>
//import foodburgcomponente from "./components/foodburgComponente.vue";
import cabeca from "./components/header";
import especialidades from "./components/especialidades";
import ambiente from "./components/ambiente";
import bebidas from "./components/bebidas";
import preco from "./components/preco";

export default {
  name: "App",
  components: {
    //foodburgcomponente,
    cabeca,
    especialidades,
    ambiente,
    bebidas,
    preco
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&family=Roboto&display=swap");
@import url('./assets/reset.css');
html {
  background-color: #181818;
}
html {
  font-family: "Roboto", sans-serif;
}
</style>
