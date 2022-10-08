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
#contenitore #contenitore-card img:hover {
  background-color: #fd6500;
  color: #fd6500;
}

#contenitore-card:hover {
  background-color: #fd6500;
  p {
    color: #ffffff;
  }
}
</style>