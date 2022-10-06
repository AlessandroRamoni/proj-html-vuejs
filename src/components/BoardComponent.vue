<template>
  <div id="barra">
    <div>
      <h2>See Our Kindergarten Photo Gallery!</h2>
      <button><a href="#">VIEW GALLERY ></a></button>
    </div>
  </div>
</template>

<script>
export default {
  name: "BoardComponent",
};
</script>

<style scoped lang="scss">
#barra {
  background-image: url(../assets/img/pattern.png);
  height: 80px;
  color: #ffffff;
  div {
    margin: 0 auto;
    max-width: 800px;
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    padding-top: 20px;
    button {
      border: 2px solid #ffffff;
      padding: 10px;
      font-size: 0.8em;
    }
  }
}
</style>