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
    <div id="contenitore-bottoni">
      <button class="bottoni"></button>
      <button class="bottoni"></button>
      <button class="bottoni"></button>
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
    padding-top: 250px;
    :first-child {
      float: left;
      margin-left: 550px;
    }
    :last-child {
      float: right;
      margin-right: 200px;
      width: 120px;
      padding-top: 30px;
    }
    img {
      width: 170px;
    }
    ::after {
      clear: both;
      display: table;
      content: "";
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
#contenitore-bottoni {
  position: absolute;
  bottom: 160px;
  left: 50%;
  transform: translate(-50%, -50%);
  .bottoni {
    width: 30px;
    height: 10px;
    margin-right: 10px;
    border: 1.5px solid #f74e00;
    position: relative;
  }
  .bottoni:last-child {
    position: absolute;
    top: -2px;
    left: 80px;
  }
}
</style>