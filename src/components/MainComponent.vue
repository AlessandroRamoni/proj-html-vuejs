<template>
  <div id="container">
    <section id="titolo">
      <div id="welcome">
        <h1>Welcome to Fable</h1>
        <p>Fable daycare, preschool and kindergarten</p>
      </div>
    </section>
    <section class="sfere">
      <div>
        <img src="../assets/img/schoolbag_alt.png" alt="" />
        <h4>Morbi Etos</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod esse,
          aliquid animi eius aspernatur aperiam nesciunt.
        </p>
      </div>

      <div>
        <img id="stroller" src="../assets/img/stroller_alt.png" alt="" />
        <h4>Congue Gravida</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod esse,
          aliquid animi eius aspernatur aperiam nesciunt.
        </p>
      </div>

      <div>
        <img src="../assets/img/globe_alt.png" alt="" />
        <h4>Maecenas Node</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod esse,
          aliquid animi eius aspernatur aperiam nesciunt.
        </p>
      </div>

      <div>
        <img id="bell" src="../assets/img/bell_alt.png" alt="" />
        <h4>Praesent Morbi</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod esse,
          aliquid animi eius aspernatur aperiam nesciunt.
        </p>
      </div>
    </section>
    <section id="philosophy">
      <div id="contenitore-section">
        <div id="sinistra">
          <button>Overview</button>
          <button>Our mission</button>
        </div>
        <div id="destra">hola</div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "MainComponent",
};
</script>

<style scoped lang="scss">
#container {
  padding-top: 50px;
}
#container #titolo #welcome h1 {
  text-align: center;
  color: #4e489b;
  font-size: 2.4em;
}
#container #titolo #welcome p {
  font-size: 1em;
  text-align: center;
  color: #4e489b;
}
.sfere {
  display: flex;
  margin: 0 auto;
  max-width: 800px;
  padding-top: 50px;
}

.sfere div img {
  background-color: #fe6500;
  object-position: center;
  border-radius: 50%;
  padding: 20px;
}
.sfere div h4,
p {
  color: #56509f;
  padding-top: 10px;
}
#stroller,
#bell {
  background-color: #56509f;
}
.sfere div {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  width: calc(100% / 4);
}
#philosophy {
  background-color: #f5f5f5;
}
#contenitore-section {
  display: flex;
  justify-content: space-around;
  max-width: 800px;
  margin: 0 auto;
  padding-top: 50px;
}
#sinistra {
  background-color: cadetblue;
  height: 200px;
}
#destra {
  background-color: burlywood;
  height: 200px;
}
</style>