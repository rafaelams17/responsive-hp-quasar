<template>
  <div class="col-5">
    <div
      class="row q-ma-md q-pa-md bg-white img-fundadores-reversa fundo-fundadores"
    >
      <div class="col q-mr-lg">
        <h2>{{ titulo }}</h2>
        <p class="descricao-fundadores">
          {{ descricao }}
        </p>
        <div class="row justify-center">
          <a
            href="https://harrypotter.fandom.com/pt-br/wiki/Rowena_Ravenclaw"
            target="_blank"
          >
            <q-btn class="btn-more col-12 col-md-auto" label="Saiba mais" />
          </a>
        </div>
      </div>
      <div class="col img-center img-fundadores-responsiva">
        <img :src="img" :alt="alt" />
      </div>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  titulo: {
    type: String,
    default: "Titulo",
  },
  descricao: {
    type: String,
    default: "",
  },
  alt: {
    type: String,
    default: "Alt",
  },
  img: {
    type: String,
    default: "Img",
  },
});
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
