<template>
  <div id="contenitore-immagine">
    <div id="contenitore">
      <div class="statistiche">
        <div>507</div>
        <h3>Our Pupils</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="statistiche">
        <div>235</div>
        <h3>Teaching Hours</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="statistiche">
        <div>100%</div>
        <h3>Satisfied Parents</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="statistiche">
        <div>1050</div>
        <h3>Meals Per Year</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
    <div id="contenitore-bottoni">
      <button class="bottoni"></button>
      <button class="bottoni"></button>
      <button class="bottoni"></button>
      <button class="bottoni"></button>
      <button class="bottoni"></button>
      <button class="bottoni"></button>
    </div>
  </div>
</template>

<script>
export default {
  name: "StatisticsComponent",
};
</script>

<style scoped lang="scss">
#contenitore-immagine {
  background-image: url(../assets/img/parallax_01.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 350px;
  #contenitore {
    display: flex;
    align-items: center;
    margin: 0 auto;
    max-width: 800px;
    padding-top: 80px;
  }
  .statistiche {
    color: #ffffff;
    text-align: center;
    div {
      border: 1px solid #ffffff;
      border-radius: 50%;
      padding: 20px 20px 20px 17px;
      font-size: 1.7em;
      font-weight: 100;
      width: 100px;
      height: 100px;
      line-height: 2.1;
      margin-left: 50px;
      object-fit: none;
    }
    h3 {
      padding-top: 30px;
    }
    p {
      padding-top: 20px;
      font-size: 0.8em;
    }
  }
}

#contenitore-bottoni {
  display: flex;
  justify-content: center;
  padding-top: 25px;
  position: relative;
  .bottoni {
    width: 30px;
    height: 10px;
    border: 1.5px solid rgb(255, 255, 255);
    margin-right: 10px;
    cursor: pointer;
    .bottoni:first-child {
      position: absolute;
      top: 20px;
      left: 20px;
    }
  }
}
.bottoni:hover {
  animation: up 1s linear;
  @keyframes up {
    from {
      transform: translate(0, 0);
    }
    to {
      transform: translate(0px, -20px);
    }
  }
}
</style>