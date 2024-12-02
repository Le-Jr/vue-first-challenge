<script setup>
import heart from "./assets/heart.svg";
import "./style.scss";
</script>

<template>
  <header>
    <div>
      <img src="./assets/vue.svg" alt="" />
      <h1>Vue</h1>
    </div>
    <input placeholder="Pesquisar no Blog" type="text" />
  </header>

  <main>
    <section>
      <div class="card">
        <div class="sectionTop">
          <p class="date">17 de ago. 2024</p>
          <img :src="heart" alt="" />
        </div>
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de programação segue tendo muita demanda de trabalho justamente pela
          velocidade com que dispositivos tecnológicos vêm avançando.
        </p>
      </div>
      <div class="card">
        <div class="sectionTop">
          <p class="date">12 de jul. 2024</p>
          <img :src="heart" alt="" />
        </div>
        <h3>GitHub agora permite fazer login sem precisar de senha</h3>
        <p>
          O GitHub anunciou nesta quarta-feira (12) o acesso a partir das
          passkeys, método de autenticação sem senhas. A novidade está
          disponível em uma versão beta pública e pode substituir a autenticação
          em dois fatores.
        </p>
      </div>
      <div class="card">
        <div class="sectionTop">
          <p class="date">1 de jun. 2024</p>
          <img :src="heart" alt="" />
        </div>
        <h3>Por que os hiperlinks são azuis em sua maioria?</h3>
        <p>
          Quem navega na internet, certamente já percebeu que ela conta com
          diversos recursos para tornar a nossa vida mais fácil. Entre essas
          opções podemos mencionar os hiperlinks – uma palavra ou termo clicável
          que direciona o leitor.
        </p>
      </div>
    </section>
  </main>
</template>

<style scoped></style>
