<template>
  <div class="BG-FUNDADORES">
    <q-layout>
      <div>
        <NavFundadores />
        <BannerFundadores />
      </div>

      <q-page-container>
        <q-page class="q-pa-xl">
          <div class="row justify-evenly container-fundadores">
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
          </div>

          <div class="row justify-evenly container-fundadores">
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
          </div>

          <div class="row justify-evenly container-fundadores">
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
        </q-page>
      </q-page-container>

      <div>
        <FooterFundadores />
      </div>
    </q-layout>
  </div>
</template>

<script setup>
import NavFundadores from "../components/NavFundadores.vue";
import BannerFundadores from "../components/BannerFundadores.vue";
import FooterFundadores from "../components/FooterFundadores.vue";
import CardFundadores from "../components/CardFundadores.vue";
</script>

<style scoped>
.BG-FUNDADORES {
  background: url("../assets/fundo.png");
}
</style>
