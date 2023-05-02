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

fundadores.value.nome = "Salazar Slytherin";
fundadores.value.img = "/img/Sonserina.svg";
fundadores.value.alt = "Sonserina";
fundadores.value.desc =
  "Salazar Slytherin foi um bruxo sangue puro nascido por volta de 976 e um dos quatro fundadores da Escola de Magia e Bruxaria de Hogwarts, sendo reconhecido por sua astúcia e determinação. Ele foi considerado um dos maiores bruxos da época, respectivamente como Ofidioglota e um habilidoso Legilimente.";
fundadores.value.href =
  "https://harrypotter.fandom.com/pt-br/wiki/Salazar_Slytherin";
</script>
