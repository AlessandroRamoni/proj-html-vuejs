<template>
  <header>
    <div id="contenitore">
      <CardComponent
        v-for="(card, index) in cards"
        :identificativo="card.id"
        :nome="card.nome"
        :immagine="card.immagine"
        :key="index"
      />
    </div>
  </header>
</template>

<script>
import CardComponent from "@/components/CardComponent.vue";

export default {
  name: "HeaderDinamico",
  props: {
    cards: Array,
  },
  components: {
    CardComponent,
  },
};
</script>

<style scoped lang="scss">
</style>