<template>
  <nav>
    <div id="contenitore-icone" v-for="(card, index) in cards" :key="index">
      <img :src="require(`@/assets/img/${card.immagine}`)" alt="" />
    </div>
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
nav {
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
</style>