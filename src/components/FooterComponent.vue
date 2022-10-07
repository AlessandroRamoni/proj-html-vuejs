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
        </div>
        <div id="recent-posts">
          <h3>RECENT POSTS</h3>
          <hr />
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
  height: 400px;
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
}
#recent-posts {
  color: #dad6d6;
  width: 25%;
}
</style>