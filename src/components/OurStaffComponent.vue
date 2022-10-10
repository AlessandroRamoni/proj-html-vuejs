<template>
  <div id="contenitore">
    <div id="welcome">
      <h1>Meet Our Staff</h1>
      <p>With education and experience in early childhood care</p>
      <img src="../assets/img/header_divider.png" alt="" />
    </div>
    <section id="testo">
      <div id="sinistra">
        <p>
          Our staff consists of three teachers and one assistant with experience
          in early childhood care.
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
    <section id="cards">
      <!-- prima riga -->
      <div class="contenitore-cards">
        <div class="card">
          <div id="card-sinistra">
            <div>
              <img src="../assets/img/team_04.jpg" alt="" />
            </div>
            <p>Ruth Richie</p>
            <span>Teacher</span>
          </div>
          <div class="card-destra">
            <img class="quote" src="../assets/img/quote.png" alt="" />
            <p>
              I have just finished my studies in Early Childhood Education, and
              I am also the kid’s yoga teacher here at Fable. I enjoy cooking,
              swimming and bike riding in my free time.
            </p>
            <div class="icone">
              <img src="../assets/img/googleplus.png" alt="" />
              <img src="../assets/img/facebook.png" alt="" />
              <img src="../assets/img/pinterest.png" alt="" />
            </div>
          </div>
        </div>
        <div class="card">
          <div id="card-sinistra">
            <div>
              <img src="../assets/img/team_03.jpg" alt="" />
            </div>
            <p>Katie Willmore</p>
            <span>Assistant Teacher</span>
          </div>
          <div class="card-destra">
            <img class="quote" src="../assets/img/quote.png" alt="" />
            <p>
              My name is Katie. I grew up and studied in Canada. This is my
              second year at Fable and love every minute of it, making the
              children’s learning experience fun.
            </p>
            <div class="icone">
              <img src="../assets/img/dribbble.png" alt="" />
              <img src="../assets/img/stumbleupon.png" alt="" />
              <img src="../assets/img/instagram.png" alt="" />
            </div>
          </div>
        </div>
      </div>
      <!-- seconda riga -->
      <div class="contenitore-cards">
        <div class="card">
          <div id="card-sinistra">
            <div>
              <img src="../assets/img/team_02.jpg" alt="" />
            </div>
            <p>Angelica Watson</p>
            <span>Lead Teacher</span>
          </div>
          <div class="card-destra">
            <img class="quote" src="../assets/img/quote.png" alt="" />
            <p>
              I hold a degree in Early Childhood Education and an advanced
              English language certificate. I have been working as a
              kindergarten teacher since 2002.
            </p>
            <div class="icone">
              <img src="../assets/img/bing.png" alt="" />
              <img src="../assets/img/skype.png" alt="" />
              <img src="../assets/img/linkedin.png" alt="" />
            </div>
          </div>
        </div>
        <div class="card">
          <div id="card-sinistra">
            <div>
              <img src="../assets/img/team_01.jpg" alt="" />
            </div>
            <p>Angela Lynn</p>
            <span>Teacher</span>
          </div>
          <div class="card-destra">
            <img class="quote" src="../assets/img/quote.png" alt="" />
            <p>
              I have completed a Graduate Diploma in Early Childhood Teaching. I
              have worked with children aged from six weeks to eight years. This
              is my second year at Fable.
            </p>
            <div class="icone">
              <img src="../assets/img/youtube.png" alt="" />
              <img src="../assets/img/twitter.png" alt="" />
              <img src="../assets/img/googleplus.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "OurStaffComponent",
};
</script>

<style scoped lang="scss">
$arancione: #fe6500;
$viola: #56509f;
$grigio-testo: #acacac;
#contenitore #welcome h1 {
  text-align: center;
  color: $viola;
  font-size: 2.4em;
}
#contenitore #welcome p {
  font-size: 0.95em;
  text-align: center;
  color: $grigio-testo;
}
#welcome {
  padding-top: 30px;
  text-align: center;
}
#welcome img {
  padding-top: 20px;
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
    color: $viola;
    font-size: 1.3em;
  }
  #destra {
    color: $grigio-testo;
    font-size: 0.9em;
  }
}

#cards {
  margin: 0 auto;
  max-width: 800px;
  padding-top: 40px;
}

#cards .contenitore-cards .card {
  width: 50%;
  display: flex;
  gap: 20px;
  align-items: end;
}

#cards .contenitore-cards .card #card-sinistra div {
  width: 180px;
}

#cards .contenitore-cards .card img {
  width: 100%;
  display: block;
}

.contenitore-cards {
  display: flex;
  gap: 20px;
  padding-bottom: 30px;
}

.card #card-sinistra p,
.card #card-destra p {
  font-size: 1em;
  color: $viola;
}

.card #card-sinistra span,
.card #card-destra span {
  font-size: 0.8em;
  color: $grigio-testo;
}

.card div p {
  font-size: 0.8em;
  color: $grigio-testo;
}
.card div span {
  font-size: 0.7em;
  color: $grigio-testo;
}

.card div:first-child {
  width: 800px;
  text-align: center;
}

.icone {
  display: flex;
  width: 40px;
  gap: 5px;
}
.icone img {
  background-color: $arancione;
}

.card-destra {
  position: relative;
}

#cards .contenitore-cards .card .card-destra .quote {
  width: 110px;
  padding: 5px 10px 5px 70px;
  border: 2px solid $arancione;
  position: absolute;
  top: -70px;
  left: -50px;
}
</style>