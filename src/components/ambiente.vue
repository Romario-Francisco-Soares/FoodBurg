<template>
  <div class="ambiente">
    <article id="sessaoAmbiente">
      <h2>Ambiente</h2>
      <div class="marcadorSessao">
        <p>1</p>
        <p>2</p>
        <p>3</p>
      </div>
      <div class="container margem">
        <div class="enunciado">
          <p>
            Temos um ambiente extremamente agradável, com área
            <br />interna e externa da hamburgueria.
          </p>
          <p>
            O local segue técnicas de ambientação, a fim de
            <br />proporcionar melhor experiência a você, contendo,
            <br />climatizador, músicas em tom baixo, parque infantil, e ainda,
            <br />área vip.
          </p>
          <p>Sim, vocês merecem ! ;)</p>
          <button>Encontre-nos</button>
        </div>
        <img src="../assets/espatulaGarfo.svg" />
      </div>
    </article>
  </div>
</template>

<script>
export default {
  name: "ambiente",
};
</script>

<style scoped>
img,
button {
  border: none;
  border-radius: 7px;
}
a {
  text-decoration: none;
  color: #fdfdfd;
}
header,
#sessaoambiente,
#sessaoPrecos {
  display: flex;
  flex-flow: column;
  width: 100%;
  height: 670px;
  background-repeat: no-repeat;
  background-size: cover;
}
header {
  background-image: url("../assets/BackGroundHeaderFoodBurg.png");
}
article {
  display: flex;
  flex-flow: column;
  height: 760px;
}
#sessaoAmbiente {
  background-image: url("../assets/BackGroundAmbienteFoodBurg.png");
  background-size: 100% 900px;
  height: 900px;
}
#sessaoPrecos {
  background-image: url("../assets/BackGroundPrecosFoodBurg.png");
}
.margem {
  width: 71.9%;
  margin: 0 auto;
}
.enunciado {
  width: 60%;
  margin-top: 120px;
}
.enunciado button {
  width: 250px;
  height: 65px;
  font-size: 1.25rem;
}
.container {
  display: flex;
}
#sessaoBebidas {
}
.containerBebidas {
  display: flex;
  width: 71.9%;
  margin: 80px auto 0 auto;
  justify-content: space-between;
}
.containerBebidas img {
  width: 170px;
}
.cervejas,
.refrigerantes,
.sucos {
  display: flex;
  flex-direction: column;
}
nav {
  display: flex;
  justify-content: center;
  margin-top: 30px;
}
nav ul {
  display: flex;
  width: 50%;
  align-items: center;
}
nav ul li {
  margin: 0 20px;
  padding: 0 5px;
  font-size: 1rem;
  color: #fdfdfd;
}
nav ul li img {
  height: 100px;
}
h1,
h3,
h2,
h4 {
  color: #fdfdfd;
  margin: 0 auto;
}
h1 {
  margin-top: 180px;
  font-size: 6.25rem;
}
h3 {
  margin-top: 20px;
  font-size: 2rem;
  font-family: "Dancing Script", cursive;
}
h2 {
  margin-top: 120px;
  font-size: 2rem;
}
h4 {
  font-size: 1.25rem;
}
.slideEspecialidades {
  display: flex;
  width: 71.9%;
  height: 400px;
  margin: 0 auto;
  margin-top: 120px;
  justify-content: space-between;
}
.imagensSlide {
  display: flex;
  width: 77.5%;
  overflow: hidden;
}
.imagensSlide img {
  min-width: 250px;
  max-height: 250px;
}
.imagem {
  margin: 0 30px;
  text-align: center;
}
.imagem p {
  margin-top: 10px;
}
.slideEspecialidades button {
  display: flex;
  min-width: 5%;
  max-height: 65%;
  align-content: end;
}
.slideEspecialidades button img {
}
.marcadorSessao {
  display: flex;
  justify-content: center;
}
.marcadorSessao p {
  width: 9px;
  height: 9px;
  margin: 25px 10px 0 10px;
  color: #171717;
  overflow: hidden;
  text-indent: -100px;
  background-color: #fdfdfd;
  border-radius: 50%;
}
p {
  font-size: 1.25rem;
  color: #fdfdfd;
  margin: 0 0 40px 0;
  line-height: 2rem;
}
.margem img {
  width: 40%;
}
table {
  width: 35%;
}
table td {
  margin-bottom: 10px;
}
table tr p {
  font-size: 2rem;
  margin: 0 0 10px 45px;
}
.precoProduto {
  width: 50px;
  color: #fdfdfd;
  font-size: 2rem;
  margin: 0 auto;
}
.tabelaItens {
  display: flex;
  box-sizing: border-box;
  flex-flow: wrap;
}
.tabelaItens p {
  margin: 0;
  font-size: 1rem;
}
.tabelaItens tr {
  display: flex;
  width: 200px;
}
.tabelaItens tr button {
  margin-top: 10px;
}
#sessaoPrecos {
  height: 900px;
}
.cardapio {
  width: 71.9%;
  height: 100%;
  margin: 90px auto 0 auto;
  justify-content: space-between;
  align-content: space-around;
  flex-flow: wrap;
}
.lanche {
  display: flex;
  width: 47%;
  height: 250px;
  opacity: 80%;
  border-radius: 10px;
  justify-content: center;
  align-items: center;
  background-color: #1a1a1a;
}
.lanche p {
  font-size: 2rem;
}
</style>
