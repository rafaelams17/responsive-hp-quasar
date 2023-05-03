<template>
  <div class="container-header row items-center">
    <!-- Header -->
    <div class="q-ml-xl col-md-4">
      <!-- Image Header -->
      <q-card-section>
        <img
          style="width: 70px; height: 70px"
          src="../assets/hogwarts-icon.png"
          alt=""
        />
      </q-card-section>
    </div>

    <div class="col-md-3 offset-md-3">
      <!-- Nav -->
      <q-card-section class="row">
        <a
          class="col"
          href="https://osmelhoreslivros.com.br/harry-potter-livros-ordem/"
          target="_blank"
        >
          <q-btn class="text-white" flat dense label="Livros" />
        </a>
        <a
          class="col q-mx-xl"
          href="https://tecnoblog.net/responde/a-ordem-cronologica-dos-filmes-para-assistir-a-saga-de-harry-potter/"
          target="_blank"
          ><q-btn class="text-white" flat dense label="Filmes"
        /></a>
        <a
          class="col"
          href="https://www.infoescola.com/biografias/j-k-rowling/"
          target="_blank"
        >
          <q-btn
            style="width: 100px"
            class="text-white"
            flat
            dense
            label="J.K. Rowling"
          />
        </a>
      </q-card-section>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
a {
  text-decoration: none;
}
</style>
