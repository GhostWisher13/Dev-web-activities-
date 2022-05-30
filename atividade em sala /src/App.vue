<template>
  <header>cabecalho</header>
  <main>Main</main>
  <footer>Rodapé</footer>
</template>
0
<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}
header,
footer {
  background-color: rgb(89, 89, 182);
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
}
main {
  min-height: 70%;
}
</style>
