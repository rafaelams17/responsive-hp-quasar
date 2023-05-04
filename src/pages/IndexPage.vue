<template>
  <q-page>
    <div class="column items-center">
      <div class="col">
        <CardGryffindor />
      </div>
      <div class="col">
        <CardHufflepuff />
      </div>

      <div class="col">
        <CardSlytherin />
      </div>

      <div class="col">
        <CardRavenclaw />
      </div>
    </div>
  </q-page>
</template>

<script setup>
import CardGryffindor from "../components/fundadores/CardGryffindor.vue";
import CardHufflepuff from "../components/fundadores/CardHufflepuff.vue";
import CardRavenclaw from "../components/fundadores/CardRavenclaw.vue";
import CardSlytherin from "../components/fundadores/CardSlytherin.vue";
</script>

<style scoped></style>
