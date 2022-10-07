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
#contenitore-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 10px;
  cursor: pointer;
  p {
    color: #4e489b;
    padding-top: 5px;
  }
}
#contenitore-card img {
  opacity: 1;
  color: #4e489b;
  filter: grayscale(50%);
}
#contenitore-card:hover {
  background-color: #fd6500;
  p {
    color: #ffffff;
  }
}
</style>