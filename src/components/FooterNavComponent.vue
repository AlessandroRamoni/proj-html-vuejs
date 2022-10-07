<template>
  <nav>
    <div id="contenitore">
      <div id="contenitore-icone" v-for="(card, index) in cards" :key="index">
        <img :src="require(`@/assets/img/${card.immagine}`)" alt="" />
      </div>
    </div>
    <p>© Fable - Children Kindergarten WordPress Theme by QuanticaLabs</p>
  </nav>
</template>

<script>
export default {
  name: "FooterNavComponent",
  props: {
    cards: Array,
  },
};
</script>

<style scoped lang="scss">
#contenitore {
  display: flex;
  justify-content: center;
  gap: 5px;
  padding-top: 30px;
}
#contenitore-icone {
  background-color: #fe6500;
  width: 40px;
  height: 40px;
}
nav p {
  text-align: center;
  padding: 30px 0px;
  color: #999594;
}
</style>