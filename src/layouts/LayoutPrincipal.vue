<template>
  <div>
    <q-card class="card-fundadores">
      <div>
        <div class="row justify-evenly container-fundadores">
          <q-card-section class="col-5">
            <div
              class="row q-ma-md q-pa-md bg-white img-fundadores-reversa fundo-fundadores"
            >
              <div class="col q-mr-lg" style="height: 500px">
                <h2>Godrico Gryffindor</h2>
                <p class="descricao-fundadores">
                  Godrico Gryffindor foi um bruxo inglês nascido por volta de
                  976 e um dos quatro fundadores da Escola de Magia e Bruxaria
                  de Hogwarts. Ele classificava seus alunos baseando-se em sua
                  coragem, determinação e ousadia. Em sua homenagem, o local o
                  qual nasceu, foi reconhecido como Godric's Hollow. O retrato
                  de Gryffindor ainda permanece no castelo de Hogwarts.
                </p>
                <div class="row justify-center">
                  <a
                    href="https://harrypotter.fandom.com/pt-br/wiki/Godrico_Gryffindor"
                    target="_blank"
                    ><q-btn
                      class="btn-more col-12 col-md-auto"
                      label="Saiba mais"
                  /></a>
                </div>
              </div>
              <div class="col img-center img-fundadores-responsiva">
                <img
                  class="img-fundadores"
                  src="/img/Grifinoria.svg"
                  alt="Grifinória"
                />
              </div>
            </div>
          </q-card-section>

          <q-card-section class="col-5">
            <div
              class="row q-ma-md q-pa-md bg-white img-fundadores-reversa fundo-fundadores"
            >
              <div class="col q-mr-lg" style="height: 500px">
                <h2>Helga Hufflepuff</h2>
                <p class="descricao-fundadores">
                  Helga Hufflepuff foi uma bruxa galesa nascida por volta de 976
                  e uma das quatro fundadoras da Escola de Magia e Bruxaria de
                  Hogwarts. Enquanto o restante dos instituidores prezavam por
                  características especiais em seus alunos, Helga aceitou a
                  todos sem preferência, embora quisesse que eles fossem leais e
                  dedicados. Seu retrato permaneceu no castelo pelo menos
                  durante a década de 1980.
                </p>
                <div class="row justify-center">
                  <a
                    href="https://harrypotter.fandom.com/pt-br/wiki/Helga_Hufflepuff"
                    target="_blank"
                  >
                    <q-btn
                      class="btn-more col-12 col-md-auto"
                      label="Saiba mais"
                    />
                  </a>
                </div>
              </div>
              <div class="col img-center img-fundadores-responsiva">
                <img
                  class="img-fundadores"
                  src="/img/Lufa-Lufa.svg"
                  alt="Lufa-Lufa"
                />
              </div>
            </div>
          </q-card-section>
        </div>

        <div class="row justify-evenly container-fundadores">
          <q-card-section class="col-5">
            <div
              class="row q-ma-md q-pa-md bg-white img-fundadores-reversa fundo-fundadores"
            >
              <div class="col q-mr-lg" style="height: 500px">
                <h2>Salazar Slytherin</h2>
                <p class="descricao-fundadores">
                  Salazar Slytherin foi um bruxo sangue puro nascido por volta
                  de 976 e um dos quatro fundadores da Escola de Magia e
                  Bruxaria de Hogwarts, sendo reconhecido por sua astúcia e
                  determinação. Ele foi considerado um dos maiores bruxos da
                  época, respectivamente como Ofidioglota e um habilidoso
                  Legilimente.
                </p>
                <div class="row justify-center">
                  <a
                    href="https://harrypotter.fandom.com/pt-br/wiki/Salazar_Slytherin"
                    target="_blank"
                    ><q-btn
                      class="btn-more col-12 col-md-auto"
                      label="Saiba mais"
                  /></a>
                </div>
              </div>
              <div class="col img-center img-fundadores-responsiva">
                <img
                  class="img-fundadores"
                  src="/img/Sonserina.svg"
                  alt="Sonserina"
                />
              </div>
            </div>
          </q-card-section>

          <q-card-section class="col-5">
            <div
              class="row q-ma-md q-pa-md bg-white img-fundadores-reversa fundo-fundadores"
            >
              <div class="col q-mr-lg" style="height: 500px">
                <h2>Rowena Ravenclaw</h2>
                <p class="descricao-fundadores">
                  Rowena Ravenclaw foi uma bruxa escocesa nascida por volta de
                  976 e uma das quatro fundadoras da Escola de Magia e Bruxaria
                  de Hogwarts. Ela era reconhecida por sua inteligência e
                  criatividade. Ravenclaw morreu em algum momento durante o
                  século XI, logo depois de adoecer fatalmente. Acredita-se que,
                  seu coração foi partido devido a fuga de sua filha Helena com
                  seu diadema. O retrato de Rowena permaneceu em Hogwarts após
                  sua morte.
                </p>
                <div class="row justify-center">
                  <a
                    href="https://harrypotter.fandom.com/pt-br/wiki/Rowena_Ravenclaw"
                    target="_blank"
                  >
                    <q-btn
                      class="btn-more col-12 col-md-auto"
                      label="Saiba mais"
                    />
                  </a>
                </div>
              </div>
              <div class="col img-center img-fundadores-responsiva">
                <img src="/img/Corvinal.svg" alt="Corvinal" />
              </div>
            </div>
          </q-card-section>
        </div>
      </div>
    </q-card>
  </div>
</template>

<script setup></script>

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

.descricao-fundadores {
  text-indent: 1.5em;
  text-align: justify;
  font-family: Arial, Helvetica, sans-serif;
}

@media (max-width: 1000px) and (min-width: 400px) {
  .img-center {
    margin: 0 auto;
  }
}

@media (max-width: 1500px) and (min-width: 100px) {
  .img-fundadores-reversa {
    display: flex;
    flex-direction: column-reverse;
  }
}

@media (max-width: 700px) {
  .container-fundadores {
    display: flex;
    flex-direction: column;
  }
  .fundo-fundadores {
    width: 500px;
  }
}

@media (max-width: 280px) and (min-width: 200px) {
  .fundo-fundadores {
    width: 150px;
  }
}

@media (max-width: 393px) and (min-width: 200px) {
  .fundo-fundadores {
    width: 300px;
  }
}

@media (max-width: 500px) and (min-width: 393px) {
  .fundo-fundadores {
    width: 340px;
  }
}

@media (max-width: 599px) and (min-width: 500px) {
  .fundo-fundadores {
    width: 480px;
  }
}

.card-fundadores {
  background: url("../assets/fundo.png");
}

.btn-more {
  border: #efc250 solid 3px;
  background-color: #0f123d;
  color: #efc250;
}

.img-fundadores-responsiva {
  display: flex;
  justify-content: center;
}
</style>
