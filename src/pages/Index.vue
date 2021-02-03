<template>
  <q-page class="flex flex-center">

    <div class="flex flex-center q-mt-md q-mr-sm">
      <q-img src="https://cdn.culturagenial.com/imagens/death-note-cartaz.jpg" width="250px" />
    </div>

    <q-card
      class="my-card text-white q-mt-md q-mr-sm"
      style="background: radial-gradient(circle, #8257e6 0%, #8257e6 100%)"
    >
      <q-card-section>
        <div class="text-h3">Livro Death Note</div><br/>
        <div class="text-subtitle2" style="font-size: 22px">R$ 32,90</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        <p>A Macabra Filmes, em parceria com a DarkSide Books,<br/> realiza um grande sonho dos fãs de horror no Brasil: a<br/> coleção completa de Livros de Sangue, de Clive Barker,<br/> chega para os leitores brasileiros com um tratamento…<br/> visceral.</p>
      </q-card-section>
      <q-btn color="green" label="COMPRAR" class="relative-position" style="margin: 10px" />
    </q-card>

  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
import {
  Quasar,
  QImg,
  QBtn,
  QToolbar,
  QToolbarTitle,
  QCard,
  QCardSection,
  QCardActions
} from 'quasar'
