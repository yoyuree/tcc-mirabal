<template>
  <header>

    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/historia">História</router-link>
      <router-link to="/apoie">Apoie</router-link>
      <router-link to="/acoes">Ações</router-link>
      <router-link to="/festival-mirabal">Festival Mirabal</router-link>
      <router-link to="/contato">Contato</router-link>
    </nav>

    <img src="../public/imagens/logo/logo-mirabal-removebg-preview.png" alt="">
  </header>
  <footer></footer>

  <router-view />
</template>

<script setup></script>
<style scoped></style>
