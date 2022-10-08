<template>
  <div id="contenitore">
    <section id="titolo">
      <div id="welcome">
        <h1>Contact Us</h1>
        <p>Our postal address and contact details</p>
        <img src="../assets/img/header_divider.png" alt="" />
      </div>
    </section>
    <section class="sfere">
      <div>
        <img src="../assets/img/envelope (1).png" alt="" />
        <h4>Postal Address</h4>
        <p>Fable Care Center 85 Fentiman Ave Ottawa, ON K1S 0T7</p>
      </div>

      <div>
        <img src="../assets/img/mobile.png" alt="" />
        <h4>Phone & E-mail</h4>
        <p>
          Phone: 1-800-64-38 Fax: 1-800-64-39 <a href="#">office@fable.com</a>
        </p>
      </div>

      <div>
        <img src="../assets/img/clock.png" alt="" />
        <h4>Business Hours</h4>
        <p>Monday – Friday 8.00 am – 5.00 pm Weekend Closed</p>
      </div>

      <div>
        <img src="../assets/img/document (1).png" alt="" />
        <h4>Sessions</h4>
        <p>
          Mornings, 8 am – 12 noon Afternoons, 1 pm – 5 pm Full Day, 8 am – 5 pm
        </p>
      </div>
    </section>
    <section id="form">
      <div id="contenitore-form-sx">
        <input type="text" placeholder="Your Name *" />
        <input type="email" placeholder="Your Email *" />
        <input type="text" placeholder="Subject" />
      </div>
      <div id="contenitore-form-dx">
        <input type="textarea" name="" id="" placeholder="Your Message *" />
      </div>
    </section>
    <button><a href="#">SEND MESSAGE</a></button>
  </div>
</template>

<script>
export default {
  name: "ContactComponent",
};
</script>

<style scoped lang="scss">
#contenitore {
  text-align: center;
  padding-bottom: 50px;
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
}
.sfere {
  display: flex;
  gap: 30px;
  margin: 0 auto;
  max-width: 800px;
  padding-top: 50px;
  text-align: center;
}
.sfere h4 {
  color: #56509f;
  padding-top: 10px;
  font-size: 1.4em;
}
.sfere p {
  color: #acacac;
  font-size: 0.8em;
}
a {
  color: #4e489b;
  text-decoration: underline;
}

#form {
  display: flex;
  padding-top: 50px;
  margin: 0 auto;
  max-width: 800px;
  text-align: left;
}
#contenitore-form-sx {
  width: 50%;
  display: flex;
  flex-direction: column;
  input {
    border: 2px solid #c5c3c3;
    padding: 5px;
    margin: 5px;
    margin-top: 10px;
  }
}
#contenitore-form-dx {
  width: 50%;
  height: 139px;
  input {
    border: 2px solid #c5c3c3;
    width: 100%;
    height: 100%;
    margin: 5px;
    padding: 5px;
    margin-top: 10px;
  }
}
input::placeholder {
  color: #969393;
  position: absolute;
  top: 5px;
  left: 5px;
}
button {
  background-color: #fe6500;
  padding: 12px;
  font-size: 0.7em;
  font-weight: 600;
  margin-top: 30px;
  a {
    text-decoration: none;
    color: #ffffff;
  }
}
</style>