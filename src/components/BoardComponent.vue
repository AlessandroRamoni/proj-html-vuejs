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
$bianco: #ffffff;
#barra {
  background-image: url(../assets/img/pattern.png);
  height: 80px;
  color: $bianco;
  div {
    margin: 0 auto;
    max-width: 800px;
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    padding-top: 18px;
    button {
      border: 2px solid $bianco;
      padding: 10px;
      font-size: 0.8em;
    }
    h2 {
      font-size: 1.7em;
      font-weight: 100;
    }
  }
}
</style>