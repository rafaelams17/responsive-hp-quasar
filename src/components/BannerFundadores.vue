<template>
  <div>
    <q-card-section class="bg-white">
      <div class="row container-main">
        <div class="col img-center" style="width: 400px">
          <q-card-section>
            <div style="width: 100%">
              <img
                class="img-main"
                src="/img/fundadores.svg"
                alt="fundadores"
              />
            </div>
          </q-card-section>
        </div>

        <div class="col q-px-md text-main">
          <h1>Os fundadores de Hogwarts</h1>
          <p class="text-fundadores">
            São quatro bruxos que criaram a Escola de Magia e Bruxaria de
            Hogwarts durante os tempos medievais, no Século X. Esses quatro
            fundadores são descritos como os mais brilhantes bruxos e bruxas de
            seu tempo, são eles Godric Gryffindor, Helga Hufflepuff, Rowena
            Ravenclaw e Salazar Slytherin. Cada um deles criaram as suas
            próprias casas: Grifinória, Lufa-Lufa, Corvinal e Sonserina. Criando
            a primeira escola de magia da Grã-Bretanha.
          </p>
        </div>
      </div>
    </q-card-section>
  </div>
</template>

<script setup></script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=Cormorant+Upright&family=Righteous&display=swap");

.img-main {
  width: 100%;
  object-fit: cover;
  object-position: bottom;
}

h1 {
  font-family: "Righteous", cursive;
  font-size: 5em;
}

.text-fundadores {
  font-family: "Cormorant Upright", serif;
  font-size: 2em;
  text-indent: 1.5em;
  text-align: justify;
}

@media (max-width: 990px) {
  .container-main {
    display: flex;
    flex-direction: column;
  }

  h1 {
    font-size: 25px;
    line-height: 1.2em;
  }

  .text-fundadores {
    font-size: 18px;
  }
}

@media (max-width: 1000px) {
  .container-main {
    display: flex;
    flex-direction: column;
  }
}
</style>
