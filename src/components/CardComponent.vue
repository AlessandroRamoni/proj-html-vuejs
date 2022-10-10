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
    nome: String,
    immagine: String,
  },
};
</script>

<style scoped lang="scss">
$arancione: #fe6500;
$viola: #56509f;
$grigio-testo: #acacac;
$bianco: #ffffff;
#contenitore-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 10px;
  cursor: pointer;
  p {
    color: $viola;
    padding-top: 5px;
    font-size: 0.8em;
  }
}
#contenitore #contenitore-card img {
  width: 25px;
  padding-top: 10px;
  color: $viola;
}

#contenitore-card:hover {
  background-color: $arancione;
  p {
    color: $bianco;
  }
}
</style>