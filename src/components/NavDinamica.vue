<template>
  <header>
    <div id="contenitore">
      <div id="logo">
        <a href="#top-up"><img src="../assets/img/logo.png" alt="" /></a>
      </div>
      <div id="contenitore-icone">
        <CardComponent
          v-for="(card, index) in cards"
          :identificativo="card.id"
          :nome="card.nome"
          :immagine="card.immagine"
          :key="index"
        />
      </div>
    </div>
  </header>
</template>

<script>
import CardComponent from "@/components/CardComponent.vue";

export default {
  name: "NavDinamica",
  props: {
    cards: Array,
  },
  components: {
    CardComponent,
  },
};
</script>

<style scoped lang="scss">
#logo {
  width: 130px;
  img {
    width: 100%;
    display: block;
  }
}
#contenitore {
  margin: 0 auto;
  max-width: 800px;
  display: flex;
  justify-content: space-between;
  #contenitore-icone {
    display: flex;
    justify-content: flex-end;
    gap: 20px;
  }
}
</style>