<template>
  <div id="contenitore">
    <section id="titolo">
      <div id="welcome">
        <h1>What's New</h1>
        <p>Keep up to date with the latest news</p>
        <img src="../assets/img/header_divider.png" alt="" />
      </div>
    </section>
    <div id="contenitore-cards">
      <div class="card">
        <span class="data">October 03, 2014</span>
        <div class="numero">42</div>
        <img src="../assets/img/blog_09.jpg" alt="" />
        <h4>Drawing and Painting Lessons</h4>
        <p>
          Magna est consectetur interdum modest dictum. Curabitur est faucibus,
          malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum
        </p>
        <hr />
        <img src="../assets/img/author.png" alt="" />
        <span>Anna Brown</span>
        <img class="category" src="../assets/img/category.png" alt="" />
        <span>Events, Fun</span>
      </div>
      <div class="card">
        <span class="data">October 03, 2014</span>
        <div class="numero">19</div>
        <img src="../assets/img/blog_10.jpg" alt="" />
        <h4>Fall Parents Meeting Day</h4>
        <p>
          Magna est consectetur interdum modest dictum. Curabitur est faucibus,
          malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum
        </p>
        <hr />
        <img src="../assets/img/author.png" alt="" />
        <span>Anna Brown</span>
        <img class="category" src="../assets/img/category.png" alt="" />
        <span>Dance, Education</span>
      </div>
      <div class="card">
        <span class="data">September 20, 2014</span>
        <div class="numero">22</div>
        <img src="../assets/img/blog_08.jpg" alt="" />
        <h4>Birthday in Kindergarten</h4>
        <p>
          Magna est consectetur interdum modest dictum. Curabitur est faucibus,
          malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum
        </p>
        <hr />
        <img src="../assets/img/author.png" alt="" />
        <span>Anna Brown</span>
        <img class="category" src="../assets/img/category.png" alt="" />
        <span>Games, General</span>
      </div>
    </div>
    <button><a href="#">GO TO BLOG ></a></button>
  </div>
</template>

<script>
export default {
  name: "NewsComponent",
};
</script>

<style scoped lang="scss">
$arancione: #fe6500;
$viola: #56509f;
$grigio-testo: #acacac;
$bianco: #ffffff;
#contenitore {
  padding-top: 50px;
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
  font-size: 1em;
  text-align: center;
  color: $grigio-testo;
  padding-top: 10px;
}
#contenitore-cards {
  max-width: 800px;
  margin: 0 auto;
  display: flex;
  gap: 20px;
  padding-top: 30px;
}
.card {
  width: 33%;
  text-align: left;
  position: relative;
  hr {
    border-top: 2px solid #eceaea;
    margin-top: 20px;
  }
}

.card > * {
  padding-top: 20px;
}

#contenitore-cards .card h4 {
  font-size: 1.1em;
  color: $viola;
  font-weight: 600;
}
#contenitore-cards .card p {
  font-size: 1em;
  color: $grigio-testo;
}
#contenitore-cards .card span {
  color: $grigio-testo;
  margin-left: 15px;
  font-size: 0.8em;
  font-weight: 600;
}
.numero {
  color: $bianco;
  background-color: $arancione;
  width: 40px;
  height: 40px;
  line-height: 0px;
  padding-left: 10px;
  position: absolute;
  right: 0;
  top: 154px;
}
.data {
  margin-left: 0 !important;
}
button {
  color: $bianco;
  background-color: $arancione;
  padding: 12px;
  font-size: 0.7em;
  font-weight: 600;
  margin-top: 30px;
}
.category {
  margin-left: 10px;
}
</style>