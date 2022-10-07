<template>
  <header>
    <div id="contenitore-immagini">
      <div id="immagini">
        <img src="../assets/img/slider_slide3_img2.png" alt="" />
        <img src="../assets/img/slider_slide3_img3.png" alt="" />
      </div>
    </div>
    <div id="barra">
      <div>
        <h2>How to Enroll Your Child to a Class?</h2>
        <button><a href="#">LEARN MORE ></a></button>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style scoped lang="scss">
#contenitore-immagini {
  background-image: url(../assets/img/slider_slide3_background.png);
  background-size: contain;
  height: 400px;
  #immagini {
    display: flex;
    justify-content: center;
    padding-top: 270px;
    align-items: baseline;
    :first-child {
      margin-left: 100px;
    }
    :last-child {
      margin-left: 200px;
      width: 100px;
      height: 65px;
    }
    img {
      width: 150px;
      // margin-left: 100px;
    }
  }
}
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
    padding-top: 18px;
    h2 {
      font-size: 1.7em;
      font-weight: 100;
    }
    button {
      border: 2px solid #ffffff;
      padding: 10px;
      font-size: 0.8em;
    }
  }
}
</style>