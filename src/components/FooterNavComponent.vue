<template>
  <nav>
    <div id="contenitore">
      <div id="contenitore-icone" v-for="(card, index) in cards" :key="index">
        <img :src="require(`@/assets/img/${card.immagine}`)" alt="" />
      </div>
    </div>
    <p>© Fable - Children Kindergarten WordPress Theme by QuanticaLabs</p>
    <button id="top-up">
      <a href="#top-up"><img src="../assets/img/go_to_top.png" alt="" /></a>
    </button>
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

nav {
  position: relative;
}
nav p {
  text-align: center;
  padding: 30px 0px;
  color: #999594;
}
button {
  background-color: #9b9b9b;
  width: 35px;
  height: 35px;
  position: absolute;
  right: 20px;
  bottom: 20px;
  cursor: pointer;
}
</style>