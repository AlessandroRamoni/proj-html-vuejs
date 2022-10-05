<template>
  <div id="container">
    <nav>
      <div id="logo">
        <img src="../assets/img/logo.png" alt="" />
      </div>
      <div id="icone">
        <div class="hover">
          <img src="../assets/img/home-2.png" alt="" />
          <p>Home</p>
        </div>
        <div class="hover">
          <img src="../assets/img/document-2.png" alt="" />
          <p>Pages</p>
        </div>
        <div class="hover">
          <img src="../assets/img/printer-2.png" alt="" />
          <p>Blog</p>
        </div>
        <div class="hover">
          <img src="../assets/img/cart-2.png" alt="" />
          <p>Shop</p>
        </div>
        <div class="hover">
          <img src="../assets/img/lab-2.png" alt="" />
          <p>Shortcodes</p>
        </div>
        <div class="hover">
          <img src="../assets/img/chat-2.png" alt="" />
          <p>Support</p>
        </div>
        <div class="hover">
          <img src="../assets/img/envelope-2.png" alt="" />
          <p>Contact</p>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavComponent",
};
</script>

<style scoped lang="scss">
#container {
  background-color: aquamarine;
  nav {
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    max-width: 800px;
    #icone {
      display: flex;
      gap: 20px;
      color: #4e489b;
    }
    .hover {
      padding: 5px;
      p {
        padding-top: 5px;
      }
    }
    .hover:hover {
      background-color: #fd6500;
    }
    #logo {
      width: 100px;
      img {
        width: 100%;
        display: block;
      }
    }
  }
}
</style>