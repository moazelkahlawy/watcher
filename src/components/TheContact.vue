<template>
  <section class="contact_section layout_padding">
    <h2 class="custom_heading text-center">NOW CONTACT US</h2>
    <div class="container mt-5 pt-5">
      <form action="">
        <div>
          <input type="text" placeholder="NAME" />
        </div>
        <div>
          <input type="email" placeholder="EMAIL" />
        </div>
        <div>
          <input type="text" placeholder="PHONE NUMBER" />
        </div>
        <div>
          <input type="text" class="message-box" placeholder="MESSAGE" />
        </div>
        <div class="d-flex justify-content-center mt-5 pt-5">
          <button>SEND</button>
        </div>
      </form>
    </div>
  </section>
</template>

<style scoped>
.layout_padding {
  padding: 75px 0;
}

.custom_heading {
  text-transform: uppercase;
  font-weight: bold;
}

.contact_section {
  color: #fff;
  background: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.3)), to(rgba(0, 0, 0, 0.3))), url(../images/contact.jpg);
  background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url("../assets/images/contact.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

.contact_section input {
  width: 100%;
  border: 0;
  border-bottom: 1px solid #ffffff;
  height: 40px;
  padding-top: 45px;
  padding-bottom: 20px;
  background-color: transparent;
  outline: none;
  color: #fff;
}

.contact_section input::-webkit-input-placeholder {
  color: #fff;
}

.contact_section input:-ms-input-placeholder {
  color: #fff;
}

.contact_section input::-ms-input-placeholder {
  color: #fff;
}

.contact_section input::placeholder {
  color: #fff;
}

.contact_section input.message-box {
  padding-top: 135px;
}

.contact_section button {
  background-color: #179dfb;
  padding: 12px 55px;
  outline: none;
  border: none;
  border: 1px solid #179dfb;
  color: #fff;
}

.contact_section button:hover {
  color: #179dfb;
  background-color: transparent;
}

@media (max-width: 768px) {
    .contact_section {
        background-size: 105px;
    }

    .contact_section input {
        background-color: transparent;
    }

    .contact_section {
        background-size: cover;
    }
}

</style>
