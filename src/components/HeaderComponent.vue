<template>
  <header>
    <div id="container">
      <div id="immagini">
        <img src="../assets/img/slider_slide3_img2.png" alt="" />
        <img src="../assets/img/slider_slide3_img3.png" alt="" />
      </div>
      <div id="barra">
        <div>
          <h2>How to Enroll Your Child to a Class?</h2>
          <button><a href="#">LEARN MORE ></a></button>
        </div>
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
#container {
  background-image: url(../assets/img/slider_slide2_background.png);
  background-repeat: no-repeat;
  background-size: cover;
  height: 400px;
  #immagini {
    display: flex;
    img {
      width: 150px;
      padding-top: 250px;
      margin-left: 300px;
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
      padding-top: 20px;
      button {
        border: 2px solid #ffffff;
        padding: 10px;
        font-size: 0.8em;
      }
    }
    // div > h2,
    // div > button {
    //   line-height: 80px;
    // }
  }
}
</style>