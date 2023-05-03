<template>
  <q-card-section class="flex q-ma-lg bg-white">
    <div class="flex column items-center" style="max-width: 1200px">
      <div class="col q-pb-md" style="max-height: 326px">
        <img class="IMG" :src="img" :alt="alt" />
      </div>

      <div class="col q-ml-md">
        <h2>{{ titulo }}</h2>
        <p class="descricao-fundadores q-pr-md q-pt-sm">
          {{ descricao }}
        </p>
        <div class="row justify-center">
          <a :href="href" target="_blank">
            <q-btn class="btn-more col-12 col-md-auto" label="Saiba mais" />
          </a>
        </div>
      </div>
    </div>
  </q-card-section>
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
    default: "Descricao",
  },
  alt: {
    type: String,
    default: "Alt",
  },
  img: {
    type: String,
    default: "Img",
  },
  href: {
    type: String,
    default: "Link",
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
  font-size: 2.5em;
  text-align: center;
}

.IMG {
  width: 100%;
  object-fit: cover;
  object-position: bottom;
}

.descricao-fundadores {
  text-indent: 1.5em;
  text-align: justify;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.3em;
}

.btn-more {
  border: #efc250 solid 3px;
  background-color: #0f123d;
  color: #efc250;
}

@media (max-width: 760px) {
  .descricao-fundadores {
    font-size: medium;
  }
  h2 {
    font-size: large;
  }
  .btn-more {
    font-size: x-small;
  }
}

@media (max-width: 430px) {
  .descricao-fundadores {
    font-size: small;
  }

  h2 {
    font-size: medium;
  }

  .btn-more {
    font-size: x-small;
  }
}

@media (max-width: 320px) {
  h2 {
    margin: 0;
  }
}
</style>
