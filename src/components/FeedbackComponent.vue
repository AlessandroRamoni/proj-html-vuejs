<template>
  <div id="contenitore">
    <img src="../assets/img/quote_alt.png" alt="" />
    <p>
      Fable kindergarten is a great place for my daughter to start her schooling
      experience. It's welcoming and safe and my daughter loves being there.
    </p>
    <hr />
    <span>Joe R. Hamblen</span>
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
  name: "FeedbackComponent",
};
</script>

<style scoped lang="scss">
#contenitore {
  background-image: url(../assets/img/parallax_02.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 350px;
  text-align: center;
  color: #ffffff;
  img {
    border: 2px solid #ffffff;
    padding: 5px;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    object-fit: none;
    object-position: center;
  }
  hr {
    color: red;
    height: 10px;
  }
  p {
    margin: 0 auto;
    max-width: 800px;
    font-size: 1.5em;
  }
}
#contenitore > * {
  margin-top: 20px;
}
#contenitore span {
  padding-top: 20px;
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
    .bottoni:first-child {
      position: absolute;
      top: 20px;
      left: 20px;
    }
  }
}
</style>