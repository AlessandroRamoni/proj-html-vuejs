<template>
  <div id="contenitore">
    <div
      id="contenitore-fotografie"
      v-for="(foto, index) in cards"
      :key="index"
    >
      <img :src="require(`@/assets/img/${foto.percorso}`)" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "CaroselloComponent",
  props: {
    cards: Array,
  },
};
</script>

<style scoped lang="scss">
</style>