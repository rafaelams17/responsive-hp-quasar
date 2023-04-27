<template>
  <div class="bg-fundadores">
    <NavFundadores />
    <BannerFundadores />
    <router-view />
    <FooterFundadores />
  </div>
</template>

<script>
import NavFundadores from "./components/NavFundadores.vue";
import BannerFundadores from "./components/BannerFundadores.vue";
import FooterFundadores from "./components/FooterFundadores.vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
  components: {
    NavFundadores,
    BannerFundadores,
    FooterFundadores,
  },
});
</script>

<style>
.bg-fundadores {
  background: url("./assets/fundo.png");
}
</style>
