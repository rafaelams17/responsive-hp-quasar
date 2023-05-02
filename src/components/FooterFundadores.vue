<template>
  <div>
    <q-card-section class="q-ma-sm footer row justify-center">
      <div class="col-3 text-center text-footer">
        <p>Desenvolvido por Rafaela</p>
      </div>

      <div class="col-3 text-center img-2">
        <div class="row">
          <a
            class="col"
            href="https://www.linkedin.com/in/rafaelasantoss/"
            target="_blank"
            ><img
              class="img-footer"
              src="../assets/linkedin.svg"
              alt="Linkedin"
          /></a>
          <a
            class="col"
            href="https://www.instagram.com/rafaa_vs23/"
            target="_blank"
            ><img
              class="img-footer"
              src="../assets/instagram.svg"
              alt="Instagram"
          /></a>
          <a class="col" href="https://github.com/rafaelams17" target="_blank"
            ><img class="img-footer" src="../assets/github.svg" alt="GitHub"
          /></a>
        </div>
      </div>
    </q-card-section>
    <q-card-section></q-card-section>
  </div>
</template>

<script setup></script>

<style scoped>
@media (max-width: 1300px) {
  .footer {
    display: flex;
    flex-direction: column;
  }
}

@media (max-width: 950px) {
  .text-footer {
    font-size: 12px;
  }

  .footer {
    display: flex;
    flex-direction: column;
  }

  .img-footer {
    width: 20px;
  }
}

@media (max-width: 370px) {
  .footer {
    display: flex;
    flex-direction: column;
  }

  .text-footer {
    width: 360px;
  }
}

.footer {
  background-color: #0f123d;
  color: #efc250;
  border: solid #efc250 4px;
  display: flex;
  align-items: center;
  font-size: 1.3em;
}

img {
  width: 25px;
}
</style>
