<template>
  <div id="contenitore-immagine">
    <div id="contenitore">
      <div class="statistiche">
        <span>507</span>
        <h3>Our Pupils</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="statistiche">
        <span>235</span>
        <h3>Teaching Hours</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="statistiche">
        <span>100%</span>
        <h3>Satisfied Parents</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="statistiche">
        <span>1050</span>
        <h3>Meals Per Year</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
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
  height: 300px;
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
    span {
      border: 1px solid #ffffff;
      border-radius: 50%;
      padding: 20px;
      line-height: 40px;
      font-size: 1.7em;
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
</style>