<template>
  <div class="q-pa-xl">
    <div class="row justify-evenly container-fundadores no-border">
      <CardFundadores
        img="/img/Grifinoria.svg"
        titulo="Godrico Gryffindor"
        descricao="Godrico Gryffindor foi um bruxo inglês nascido por volta de 976
                e um dos quatro fundadores da Escola de Magia e Bruxaria de
                Hogwarts. Ele classificava seus alunos baseando-se em sua
                coragem, determinação e ousadia. Em sua homenagem, o local o
                qual nasceu, foi reconhecido como Godric's Hollow. O retrato de
                Gryffindor ainda permanece no castelo de Hogwarts."
      />

      <CardFundadores
        img="/img/Lufa-Lufa.svg"
        alt="Lufa-Lufa"
        titulo="Helga Hufflepuff"
        descricao="Helga Hufflepuff foi uma bruxa galesa nascida por volta de 976 e
                uma das quatro fundadoras da Escola de Magia e Bruxaria de
                Hogwarts. Enquanto o restante dos instituidores prezavam por
                características especiais em seus alunos, Helga aceitou a todos
                sem preferência, embora quisesse que eles fossem leais e
                dedicados. Seu retrato permaneceu no castelo pelo menos durante
                a década de 1980."
      />
    </div>

    <div class="row justify-evenly container-fundadores">
      <CardFundadores
        img="/img/Sonserina.svg"
        alt="Lufa-Lufa"
        titulo="Salazar Slytherin"
        descricao="Salazar Slytherin foi um bruxo sangue puro nascido por volta de
                976 e um dos quatro fundadores da Escola de Magia e Bruxaria de
                Hogwarts, sendo reconhecido por sua astúcia e determinação. Ele
                foi considerado um dos maiores bruxos da época, respectivamente
                como Ofidioglota e um habilidoso Legilimente."
      />

      <CardFundadores
        img="/img/Corvinal.svg"
        alt="Corvinal"
        titulo="Rowena Ravenclaw"
        descricao="Rowena Ravenclaw foi uma bruxa escocesa nascida por volta de 976
                e uma das quatro fundadoras da Escola de Magia e Bruxaria de
                Hogwarts. Ela era reconhecida por sua inteligência e
                criatividade. Ravenclaw morreu em algum momento durante o século
                XI, logo depois de adoecer fatalmente. Acredita-se que, seu
                coração foi partido devido a fuga de sua filha Helena com seu
                diadema. O retrato de Rowena permaneceu em Hogwarts após sua
                morte."
      />
    </div>
  </div>
</template>

<script setup>
import CardFundadores from "../components/CardFundadores.vue";
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=Cormorant+Upright&family=Righteous&display=swap");

a {
  text-decoration: none;
}
h2 {
  font-family: "Cinzel", serif;
  font-size: 2em;
  text-align: center;
}

@media (max-width: 700px) {
  .container-fundadores {
    display: flex;
    flex-direction: column;
  }
}
</style>
