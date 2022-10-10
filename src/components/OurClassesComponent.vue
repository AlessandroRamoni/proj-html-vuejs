<template>
  <div id="contenitore">
    <section id="titolo">
      <div id="welcome">
        <h1>Our Classes</h1>
        <p>Our preschool program has four dedicated classes</p>
        <img src="../assets/img/header_divider.png" alt="" />
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
    <!-- prime due tessere -->
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
          <div class="eta">
            <div>
              <p>2-3</p>
              <p>Years olds</p>
            </div>
            <div>
              <p>12</p>
              <p>Class size</p>
            </div>
          </div>
        </div>
        <div class="immagine">
          <img src="../assets/img/class_02-690x506.jpg" alt="" />
          <button>READ MORE ></button>
        </div>
      </div>
    </section>
    <!-- altre due tessere -->
    <section id="padding-bottom" class="tessere">
      <div class="card">
        <div class="scheda">
          <h1>Tenderhearts</h1>
          <span>Class name</span>
          <div class="eta">
            <div>
              <p>3-4</p>
              <p>Years olds</p>
            </div>
            <div>
              <p>15</p>
              <p>Class size</p>
            </div>
          </div>
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
          <div class="eta">
            <div>
              <p>4-5</p>
              <p>Years olds</p>
            </div>
            <div>
              <p>20</p>
              <p>Class size</p>
            </div>
          </div>
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
          <div class="mission">
            <div>
              <img src="../assets/img/toy.png" alt="" />
            </div>
            <h3>Learning & Fun</h3>
            <p>Praesent modea est gravida node vehicula luctus.</p>
          </div>
          <div class="mission">
            <div>
              <img src="../assets/img/meal.png" alt="" />
            </div>
            <h3>Healthy Meals</h3>
            <p>Terminal interdum a eleifend maecenas est morbi.</p>
          </div>
          <div class="mission">
            <div>
              <img src="../assets/img/school.png" alt="" />
            </div>
            <h3>Friendly Place</h3>
            <p>Terminal interdum a eleifend maecenas est morbi.</p>
          </div>
          <div class="mission">
            <div>
              <img src="../assets/img/shield.png" alt="" />
            </div>
            <h3>Children Safety</h3>
            <p>Praesent modea est gravida node vehicula luctus.</p>
          </div>
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
#welcome {
  text-align: center;
}
#welcome img {
  padding-top: 20px;
}

#contenitore #titolo #welcome h1 {
  text-align: center;
  color: #4e489b;
  font-size: 2.4em;
}
#contenitore #titolo #welcome p {
  font-size: 1em;
  text-align: center;
  color: #acacac;
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
  padding-top: 30px;
}
.card {
  display: flex;
  width: 50%;
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
  padding-top: 30px;
  font-size: 0.9em;
}
.eta div {
  flex-basis: 50%;
}
.eta div p:last-child {
  color: rgb(216, 207, 207);
  font-size: 0.8em;
  font-weight: 800;
  padding-top: 5px;
}

.eta div:last-child {
  border-left: 2px solid rgb(216, 207, 207);
}

.eta div p:first-child {
  font-weight: 600;
}

#goals {
  background-color: #f5f5f5;
  padding-bottom: 40px;
}
#contenitore-goals {
  margin: 0 auto;
  max-width: 800px;
  display: flex;
  padding-top: 40px;
}
#padding-bottom {
  padding-bottom: 30px;
}
#contenitore-goals-sinistra {
  width: 50%;
}
#contenitore-goals-sinistra p:first-child {
  color: #4e489b;
  font-size: 1.3em;
}
#contenitore-goals-sinistra p:nth-of-type(2) {
  color: #8e8e8e;
  font-size: 0.8em;
  padding-top: 20px;
}
#contenitore-goals-sinistra ul {
  padding-top: 20px;
}
#contenitore-goals-sinistra ul li {
  display: flex;
  margin-top: 10px;
}

#contenitore-goals-sinistra ul li span {
  font-size: 0.8em;
  color: #8e8e8e;
  padding-left: 10px;
}
#contenitore-goals-destra {
  display: flex;
  flex-wrap: wrap;
  width: 50%;
}
.mission {
  width: calc(100% / 2);
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.mission h3 {
  font-size: 1.3em;
  color: #4e489b;
}
.mission p {
  font-size: 0.8em;
  color: #8e8e8e;
  padding-top: 10px;
}
.mission div {
  width: 70px;
}
.mission img {
  background-color: #ffffff;
  border-radius: 50%;
  padding: 10px;
  object-fit: none;
  width: 100%;
}
</style>