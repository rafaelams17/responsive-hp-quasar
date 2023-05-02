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

fundadores.value.nome = "Helga Hufflepuff";
fundadores.value.img = "/img/Lufa-Lufa.svg";
fundadores.value.alt = "Lufa-Lufa";
fundadores.value.desc =
  "Helga Hufflepuff foi uma bruxa galesa nascida por volta de 976 e uma das quatro fundadoras da Escola de Magia e Bruxaria de Hogwarts. Enquanto o restante dos instituidores prezavam por características especiais em seus alunos, Helga aceitou a todos sem preferência, embora quisesse que eles fossem leais e dedicados. Seu retrato permaneceu no castelo pelo menos durante a década de 1980.";
fundadores.value.href =
  "https://harrypotter.fandom.com/pt-br/wiki/Helga_Hufflepuff";
</script>
