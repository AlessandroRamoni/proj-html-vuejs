<template>
  <div id="contenitore">
    <section id="titolo">
      <div id="welcome">
        <h1>Welcome to Fable</h1>
        <p>Fable daycare, preschool and kindergarten</p>
        <img src="../assets/img/header_divider.png" alt="" />
      </div>
    </section>
    <section class="sfere">
      <div class="bolla">
        <div class="contenitore-bolla">
          <img src="../assets/img/schoolbag_alt.png" alt="" />
        </div>
        <h4>Morbi Etos</h4>
        <p>
          Praesent interdum est gravida vehicula est node maecenas loareet morbi
          a dosis luctus novum est praesent.
        </p>
      </div>

      <div class="bolla">
        <div class="contenitore-bolla">
          <img id="stroller" src="../assets/img/stroller_alt.png" alt="" />
        </div>
        <h4>Congue Gravida</h4>
        <p>
          Elipsis magna a terminal nulla elementum morbi elite forte maecenas
          est magna etos interdum vitae est.
        </p>
      </div>
      <div class="bolla">
        <div class="contenitore-bolla">
          <img src="../assets/img/globe_alt.png" alt="" />
        </div>
        <h4>Maecenas Node</h4>
        <p>
          Praesent interdum est gravida vehicula est node maecenas loareet morbi
          a dosis luctus novum est praesent.
        </p>
      </div>
      <div class="bolla">
        <div class="contenitore-bolla">
          <img id="bell" src="../assets/img/bell_alt.png" alt="" />
        </div>
        <h4>Praesent Morbi</h4>
        <p>
          Elipsis magna a terminal nulla elementum morbi elite forte maecenas
          est magna etos interdum vitae est.
        </p>
      </div>
    </section>
    <section id="philosophy">
      <div id="contenitore-section">
        <div id="sinistra">
          <button id="overview">Overview</button>
          <button id="mission">Our Mission</button>
          <p>
            Our philosophy is learning through play as we offer a stimulating
            environment for children.
          </p>
          <div class="orizzontale">
            <img src="../assets/img/clock_alt.png" alt="" />
            <div id="right">
              <h3>Full Day Session</h3>
              <p>
                Pulvinar est metro ligula blandit maecenas retrum gravida
                cuprum. Maecenas node estibulum.
              </p>
            </div>
          </div>
          <div class="orizzontale">
            <img src="../assets/img/diagram_alt.png" alt="" />
            <div id="right">
              <h3>Varied Classes</h3>
              <p>
                Pulvinar est metro ligula blandit maecenas retrum gravida
                cuprum. Maecenas node estibulum.
              </p>
            </div>
          </div>
        </div>
        <div id="destra">
          <div id="foto-grande">
            <img src="../assets/img/gallery_01.jpg" alt="" />
          </div>
          <div id="slider">
            <img src="../assets/img/gallery_01-690x506.jpg" alt="" />
            <img src="../assets/img/gallery_07-690x506.jpg" alt="" />
            <img src="../assets/img/gallery_08-690x506.jpg" alt="" />
          </div>
        </div>
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
$arancione: #fe6500;
$viola: #56509f;
$grigio-testo: #acacac;
#contenitore {
  padding-top: 50px;
}
#welcome {
  text-align: center;
}

#welcome img {
  padding-top: 20px;
}
#contenitore #titolo #welcome h1 {
  text-align: center;
  color: $viola;
  font-size: 2.4em;
}
#contenitore #titolo #welcome p {
  font-size: 0.95em;
  text-align: center;
  color: $grigio-testo;
}
.sfere {
  display: flex;
  margin: 0 auto;
  max-width: 800px;
  padding-top: 50px;
  padding-bottom: 50px;
}

.contenitore-bolla {
  width: 120px;
  height: 120px;
}
.sfere .bolla img {
  background-color: $arancione;
  border-radius: 50%;
  padding: 20px;
  width: 100%;
  object-fit: none;
}

.sfere h4 {
  font-size: 1.2em;
  font-weight: 600;
}

.sfere p {
  font-size: 0.8em;
}

.sfere .bolla h4,
p {
  color: $viola;
  padding-top: 10px;
}
#stroller,
#bell {
  background-color: $viola;
}
.sfere .bolla {
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
  padding-bottom: 50px;
}
#sinistra {
  flex-basis: 50%;
  background-color: #f5f5f5;
  #mission {
    margin-left: 15px;
    border-bottom: 2px solid #dfdfdf;
  }
  > p {
    font-size: 1.4em;
    margin-top: 20px;
    font-weight: 500;
  }
  .orizzontale {
    display: flex;
    padding-top: 20px;
    gap: 20px;
    align-items: center;
  }
  .orizzontale #right p {
    color: #746d69;
    font-size: 1.2em;
  }
  .orizzontale #right h3 {
    font-size: 1.8em;
    color: $viola;
  }

  .orizzontale img {
    background-color: $arancione;
    border-radius: 50%;
    flex-basis: 100px;
    object-fit: none;
  }
  #right {
    font-size: 0.7em;
  }
}
#overview {
  background-color: $arancione;
  color: #f5f5f5;
  padding: 12px 20px;
  font-size: 0.8em;
  cursor: pointer;
}
#mission {
  background-color: #f5f5f5;
  color: #554f4c;
  padding: 12px 20px;
  font-size: 0.8em;
  cursor: pointer;
}
#destra {
  flex-basis: 50%;
  #foto-grande {
    width: 100%;
  }

  #slider {
    display: flex;
    gap: 5px;
    max-width: calc(100% / 3 - 3px);
  }
}
</style>