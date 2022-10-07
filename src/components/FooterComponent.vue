<template>
  <div id="contenitore">
    <footer>
      <div id="contenitore-footer">
        <div id="about-us">
          <h3>ABOUT US</h3>
          <hr />
          <p>
            Elipsis magna a nulla elite forte maecenas est elementum magna etos
            interdum movum morbi vehicula morbi.
          </p>
          <img src="../assets/img/logo_footer.png" alt="" />
        </div>
        <div id="archives">
          <h3>ARCHIVES</h3>
          <hr />
          <ul>
            <li><a href="#">OCTOBER 2014 (2)</a></li>
            <li><a href="#">SEPTEMBER 2014 (2)</a></li>
            <li><a href="#">AUGUST 2014 (2)</a></li>
            <li><a href="#">JULY 2014 (2)</a></li>
            <li><a href="#">JUNE 2014 (2)</a></li>
            <li><a href="#">MAY 2014 (1)</a></li>
          </ul>
        </div>
        <div id="our-features">
          <h3>OUR FEATURES</h3>
          <hr />
          <p>
            Nunc gravida rutrum mauris vehin hasellus ac pretium augue vivamul
            lacus ligul mattis ac vene:
          </p>
          <ul>
            <li>
              <img src="../assets/img/style_4_alt.png" alt="" />
              <span>Friendly and welcoming place</span>
            </li>
            <li>
              <img src="../assets/img/style_4_alt.png" alt="" />
              <span>Science and art classes</span>
            </li>
            <li>
              <img src="../assets/img/style_4_alt.png" alt="" />
              <span>Positive learning environment</span>
            </li>
            <li>
              <img src="../assets/img/style_4_alt.png" alt="" />
              <span>Educational field trips</span>
            </li>
            <li>
              <img src="../assets/img/style_4_alt.png" alt="" />
              <span>Writing and reading classes</span>
            </li>
            <li>
              <img src="../assets/img/style_4_alt.png" alt="" />
              <span>Science and art classes</span>
            </li>
          </ul>
        </div>
        <div id="recent-posts">
          <h3>RECENT POSTS</h3>
          <hr />
          <div class="contenitore-card">
            <div class="contenitore-immagine">
              <img src="../assets/img/blog_09-150x150.jpg" alt="" />
            </div>
            <div class="contenitore-testo">
              <p>Drawing and Painting Lessons</p>
              <div>
                <img src="../assets/img/date_footer.png" alt="" />
                <span>October 03, 2014</span>
              </div>
            </div>
          </div>
          <div class="contenitore-card">
            <div class="contenitore-immagine">
              <img src="../assets/img/blog_10-150x150.jpg" alt="" />
            </div>
            <div class="contenitore-testo">
              <p>Fall Parents Meeting Day</p>
              <div>
                <img src="../assets/img/date_footer.png" alt="" />
                <span>October 03, 2014</span>
              </div>
            </div>
          </div>
          <div class="contenitore-card">
            <div class="contenitore-immagine">
              <img src="../assets/img/blog_08-150x150.jpg" alt="" />
            </div>
            <div class="contenitore-testo">
              <p>Birthday In kindergarten</p>
              <div>
                <img src="../assets/img/date_footer.png" alt="" />
                <span>September 20, 2014</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>

<style scoped lang="scss">
#contenitore {
  background-image: url(../assets/img/pattern.png);
}
footer {
  margin: 0 auto;
  max-width: 800px;
}
#contenitore-footer {
  display: flex;
  gap: 20px;
}
#about-us {
  color: #dad6d6;
  width: 25%;
  h3 {
    padding-top: 30px;
  }
  p {
    padding-top: 30px;
    font-size: 0.9em;
  }
  img {
    padding-top: 30px;
  }
}
#archives {
  color: #dad6d6;
  width: 25%;
  h3 {
    padding-top: 30px;
  }
  ul {
    padding-top: 30px;
  }
  li {
    border: 1px solid #a8a1a1;
    margin-top: 10px;
  }
  li:first-child {
    margin-top: 0px;
  }
  a {
    padding: 10px;
    font-size: 0.8em;
  }
}
#our-features {
  color: #dad6d6;
  width: 25%;
  h3 {
    padding-top: 30px;
  }
  p {
    padding-top: 30px;
    font-size: 0.9em;
  }
  ul {
    padding-top: 20px;
  }
  ul li {
    display: flex;
    margin-bottom: 5px;
  }
  ul li span {
    font-size: 0.6em;
    padding-left: 10px;
  }
}
#recent-posts {
  color: #dad6d6;
  width: 25%;
  h3 {
    padding-top: 30px;
  }
  .contenitore-card {
    padding-top: 30px;
    display: flex;
    gap: 10px;
  }
  .contenitore-immagine {
    width: 100px;
    img {
      width: 100%;
      display: block;
    }
  }
  .contenitore-testo div {
    display: flex;
    align-items: center;
    padding-top: 10px;
  }

  .contenitore-testo p {
    font-size: 0.9em;
  }
  span {
    padding-left: 10px;
    font-size: 0.5em;
  }
}
</style>