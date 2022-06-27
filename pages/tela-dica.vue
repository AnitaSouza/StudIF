<template>
  <div>
    <barraNav></barraNav>
    <b-container class="container">
      <img src="lampada.webp" width="320" height="205" />
      <center><p>Dica do dia</p></center>

      <b-container class="DicadoDia">
        <p>
          Leia, mas escreva tambem. O estudo feito só por meio da leitura não é
          tão eficiente. O estudante pode se pegar facilmente distraido no
          decorrer das páginas. Por isso, escreva! Faça esquemas, transcreva
          partes importantes e organize resumos. Quem escreve consegue assimilar
          melhor o conteúdo e tê-lo por mais tempo na mente.
        </p>
      </b-container>

      <b-container class="BancodeDicas">
        <center><p>Banco de Dicas</p></center>
      </b-container>
      <b-container class="AddDicas">
        <center><p>+ Adicionar Dicas</p></center>
      </b-container>
    </b-container>
  </div>
</template>

<script>
import barraNav from '~/components/barraNav.vue'
export default {
  components: { barraNav },
  name: 'IndexPage',
}
</script>
<style>
html,
body {
  height: 100%;
  width: 100%;
  background-color: rgb(255, 255, 255);
}
.container img {
  max-width: 200px;
  display: block;
  margin: 0 auto;
}
.DicadoDia,
.BancodeDicas,
.AddDicas {
  background-color: #C9E9AF;
}
</style>