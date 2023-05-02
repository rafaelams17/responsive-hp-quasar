<template>
  <CardFundadores
    :img="fundadores.img"
    :alt="fundadores.alt"
    :titulo="fundadores.nome"
    :descricao="fundadores.desc"
    :href="fundadores.href"
  />
</template>

<script setup>
import CardFundadores from "../CardFundadores.vue";
import { ref } from "vue";

const fundadores = ref({
  nome: "",
  img: "",
  alt: "",
  desc: "",
  href: "",
});

fundadores.value.nome = "Rowena Ravenclaw";
fundadores.value.img = "/img/Corvinal.svg";
fundadores.value.alt = "Corvinal";
fundadores.value.desc =
  "Rowena Ravenclaw foi uma bruxa escocesa nascida por volta de 976 e uma das quatro fundadoras da Escola de Magia e Bruxaria de                 Hogwarts. Ela era reconhecida por sua inteligência e criatividade. Ravenclaw morreu em algum momento durante o século XI, logo depois de adoecer fatalmente. Acredita-se que, seu coração foi partido devido a fuga de sua filha Helena com seu diadema. O retrato de Rowena permaneceu em Hogwarts após sua morte.";
fundadores.value.href =
  "https://harrypotter.fandom.com/pt-br/wiki/Rowena_Ravenclaw";
</script>
