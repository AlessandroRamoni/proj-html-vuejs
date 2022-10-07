<template>
  <div id="contenitore">
    <div id="contenitore-card">
      <img :src="require(`@/assets/img/${immagine}`)" alt="" />

      <p>{{ nome }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardComponent",
  props: {
    identificativo: Number,
    nome: String,
    immagine: String,
  },
};
</script>

<style scoped lang="scss">
#contenitore {
  display: flex;
}
#contenitore-card {
  flex-basis: 50px;
}
</style>