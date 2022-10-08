<template>
  <div id="contenitore">
    <div id="contenitore-card">
      <img :src="require(`@/assets/img/svg/${immagine}`)" alt="" />
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
    font-size: 0.8em;
  }
}
#contenitore #contenitore-card img {
  width: 25px;
  padding-top: 10px;
  color: #4e489b;
}

#contenitore-card:hover {
  background-color: #fd6500;
  p {
    color: #ffffff;
  }
}
#contenitore-card:hover img {
  background-image: url(../assets/img/home-2.png);
  object-position: 30px 30px;
  width: 32px;
  height: 32px;
}
</style>