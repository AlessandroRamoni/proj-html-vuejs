<template>
  <div id="contenitore">
    <section id="titolo">
      <div id="welcome">
        <h1>Our Classes</h1>
        <p>Our preschool program has four dedicated classes</p>
      </div>
    </section>
    <section id="testo">
      <div id="sinistra">
        <p>
          We provided four classes with nine to twenty children each aged twelve
          month to five years of age.
        </p>
      </div>
      <div id="destra">
        <p>
          Praesent arcu gravida vehicula est node maecenas loareet morbi a dosis
          luctus. Urna eget lacinia eleifend praesent luctus a arcu quis
          facilisis venenatis. Aenean interdum, nibh vitae sodales, magna ante
          feugiat elit maecenas.
        </p>
      </div>
    </section>
    <section class="tessere">
      <div class="card">
        <div class="scheda">
          <h1>Little Lambs</h1>
          <span>Class name</span>
          <div class="eta">
            <div>
              <p>12-24</p>
              <p>Month olds</p>
            </div>
            <div>
              <p>9</p>
              <p>Class size</p>
            </div>
          </div>
        </div>
        <div class="immagine">
          <img src="../assets/img/class_01-690x506.jpg" alt="" />
          <button>READ MORE ></button>
        </div>
      </div>
      <div class="card">
        <div class="scheda">
          <h1>Bouncy Bears</h1>
          <span>Class name</span>
        </div>
        <div class="immagine">
          <img src="../assets/img/class_02-690x506.jpg" alt="" />
          <button>READ MORE ></button>
        </div>
      </div>
    </section>
    <section class="tessere">
      <div class="card">
        <div class="scheda">
          <h1>Tenderhearts</h1>
          <span>Class name</span>
        </div>
        <div class="immagine">
          <img src="../assets/img/class_03-690x506.jpg" alt="" />
          <button>READ MORE ></button>
        </div>
      </div>
      <div class="card">
        <div class="scheda">
          <h1>Shining Stars</h1>
          <span>Class name</span>
        </div>
        <div class="immagine">
          <img src="../assets/img/class_04-690x506.jpg" alt="" />
          <button>READ MORE ></button>
        </div>
      </div>
    </section>
    <section id="goals">
      <div id="contenitore-goals">
        <div id="contenitore-goals-sinistra">
          <p>
            We have been educating children for over fifteen years. Our goal is
            to create a place that engages each child.
          </p>
          <p>
            Praesent arcu gravida vehicula est node maecenas loareet morbi a
            dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis
            facilisis venenatis aenean interdum.
          </p>
          <ul>
            <li>
              <img src="../assets/img/style_1.png" alt="" />
              <span>Comprehensive reporting on individual achievement</span>
            </li>
            <li>
              <img src="../assets/img/style_1.png" alt="" />
              <span>Educational field trips and school presentations</span>
            </li>
            <li>
              <img src="../assets/img/style_1.png" alt="" />
              <span>Individual attention in a small-class setting</span>
            </li>
            <li>
              <img src="../assets/img/style_1.png" alt="" />
              <span>Learning program with after-school care</span>
            </li>
            <li>
              <img src="../assets/img/style_1.png" alt="" />
              <span>Opportunities to carry out scientific investigations</span>
            </li>
            <li>
              <img src="../assets/img/style_1.png" alt="" />
              <span>Positive learning environment for your child</span>
            </li>
          </ul>
        </div>
        <div id="contenitore-goals-destra">
          <p>holaaaaaa</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "OurClassesComponent",
};
</script>

<style scoped lang="scss">
#titolo {
  padding-top: 30px;
  margin: 0 auto;
  max-width: 800px;
}
#contenitore #titolo #welcome h1 {
  text-align: center;
  color: #4e489b;
  font-size: 2.4em;
}
#contenitore #titolo #welcome p {
  font-size: 1em;
  text-align: center;
  color: #4e489b;
  padding-top: 5px;
}
#testo {
  margin: 0 auto;
  max-width: 800px;
  padding-top: 40px;
  display: flex;
  gap: 20px;
  div {
    flex-basis: 50%;
  }
  #sinistra {
    color: #4e489b;
    font-size: 1.3em;
  }
  #destra {
    color: #8e8e8e;
    font-size: 0.9em;
  }
}
.tessere {
  margin: 0 auto;
  max-width: 800px;
  display: flex;
  gap: 20px;
  padding-top: 25px;
}
.card {
  display: flex;
}
.tessere .card .scheda {
  background-color: #56509f;
}
.immagine {
  position: relative;
}
.scheda {
  color: #ffffff;
  padding: 10px;
}
.scheda span {
  font-size: 0.7em;
}
.scheda,
.immagine {
  flex-basis: 50%;
}
.immagine img {
  display: block;
}
.immagine button {
  background-color: #fe6500;
  color: #ffffff;
  padding: 10px;
  font-weight: 800;
  font-size: 0.6em;
  position: absolute;
  bottom: 0;
  right: 0;
  cursor: pointer;
}
.eta {
  display: flex;
  text-align: center;
}
.eta div {
  flex-basis: 50%;
}
#goals {
  background-color: #f5f5f5;
}
#contenitore-goals {
  margin: 0 auto;
  max-width: 800px;
  display: flex;
}
#contenitore-goals-sinistra {
  flex-basis: 50%;
}
#contenitore-goals-sinistra {
  flex-basis: 50%;
}
</style>