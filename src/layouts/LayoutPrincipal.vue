<template>
  <div class="BG-FUNDADORES">
    <q-layout>
      <div>
        <!-- Área do Cabeçalho -->
        <NavFundadores />
        <BannerFundadores />
      </div>

      <q-page-container>
        <!-- Área Principal -->
        <IndexPage />
      </q-page-container>

      <div>
        <!-- Área do Rodapé -->
        <FooterFundadores />
      </div>
    </q-layout>
  </div>
</template>

<script setup>
import NavFundadores from "../components/NavFundadores.vue";
import BannerFundadores from "../components/BannerFundadores.vue";
import FooterFundadores from "../components/FooterFundadores.vue";
import IndexPage from "src/pages/IndexPage.vue";
</script>

<style scoped>
.BG-FUNDADORES {
  background: url("../assets/fundo.png");
}
</style>
