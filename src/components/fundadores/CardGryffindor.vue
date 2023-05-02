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

fundadores.value.nome = "Godrico Gryffindor";
fundadores.value.img = "/img/Grifinoria.svg";
fundadores.value.alt = "Grifinória";
fundadores.value.desc =
  "Godrico Gryffindor foi um bruxo inglês nascido por volta de 976 e um dos quatro fundadores da Escola de Magia e Bruxaria de Hogwarts. Ele classificava seus alunos baseando-se em sua coragem, determinação e ousadia. Em sua homenagem, o local o qual nasceu, foi reconhecido como Godric's Hollow. O retrato de Gryffindor ainda permanece no castelo de Hogwarts.";
fundadores.value.href =
  "https://harrypotter.fandom.com/pt-br/wiki/Godrico_Gryffindor";
</script>
