<template>
  <section class="client_section layout_padding-bottom">
    <div class="container">
      <h3 class="custom_heading">Testimonial</h3>
      <p class="font-weight-bold">
        It is a long established fact that a reader will be distracted by the
        readable content of a page
      </p>
    </div>
    <div class="container"></div>
    <div
      id="carouselExample2Controls"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="container">
            <div class="row">
              <div class="col-12">
                <div class="detail_box">
                  <div class="img_box">
                    <img src="../assets/images/client.jpg" alt="" />
                  </div>
                  <div class="name_box">
                    <h5>Sandy Den</h5>
                    <h6>Many Variations</h6>
                  </div>
                </div>
                <div class="detail_text">
                  <p>
                    There are many variations of passages of Lorem Ipsum
                    available, but the majority have suffered alteration in some
                    form, by injected humour, or randomised words which don't
                    look even slightly believable. If you are going to use a
                    passage of Lorem Ipsum, you need to beThere are many
                    variations of passages
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="container">
            <div class="row">
              <div class="col-12">
                <div class="detail_box">
                  <div class="img_box">
                    <img src="../assets/images/client.jpg" alt="" />
                  </div>
                  <div class="name_box">
                    <h5>Sandy Den</h5>
                    <h6>Many Variations</h6>
                  </div>
                </div>
                <div class="detail_text">
                  <p>
                    There are many variations of passages of Lorem Ipsum
                    available, but the majority have suffered alteration in some
                    form, by injected humour, or randomised words which don't
                    look even slightly believable. If you are going to use a
                    passage of Lorem Ipsum, you need to beThere are many
                    variations of passages
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="container">
            <div class="row">
              <div class="col-12">
                <div class="detail_box">
                  <div class="img_box">
                    <img src="../assets/images/client.jpg" alt="" />
                  </div>
                  <div class="name_box">
                    <h5>Sandy Den</h5>
                    <h6>Many Variations</h6>
                  </div>
                </div>
                <div class="detail_text">
                  <p>
                    There are many variations of passages of Lorem Ipsum
                    available, but the majority have suffered alteration in some
                    form, by injected humour, or randomised words which don't
                    look even slightly believable. If you are going to use a
                    passage of Lorem Ipsum, you need to beThere are many
                    variations of passages
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExample2Controls"
        role="button"
        data-bs-slide="prev"
      >
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExample2Controls"
        role="button"
        data-bs-slide="next"
      >
      </a>
    </div>
  </section>
</template>


<style scoped>
.layout_padding-bottom {
  padding-bottom: 75px;
}

.client_section .row {
  padding: 25px 0;
}

.client_section .row .col-12 {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.client_section .detail_box {
  min-width: 150px;
  margin-right: 25px;
  text-align: center;
}

.client_section .detail_box img {
  width: 100%;
}

.client_section .detail_box h5 {
  font-weight: bold;
}

.client_section .detail_box h6 {
  color: #0b3275;
}

.client_section .detail_box .name_box {
  margin-top: 15px;
}

.client_section .detail_text {
  padding-top: 10px;
}

.client_section #carouselExampleControls,
.client_section .carousel-inner,
.client_section .carousel-item {
  height: 100%;
}

.client_section .carousel-control-prev,
.client_section .carousel-control-next {
  position: absolute;
  top: 50%;
  width: 50px;
  height: 45px;
  border: none;
  opacity: 1;
  background-repeat: no-repeat;
  background-size: 10px;
  background-position: center;
  background-color: #c1dcf9;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}

.client_section .carousel-control-prev:hover,
.client_section .carousel-control-next:hover {
  background-color: #f2d8b9;
}

.client_section .carousel-control-prev {
  left: 2%;
  background-image: url("../assets/images/prev.png");
}

.client_section .carousel-control-next {
  right: 2%;
  background-image: url("../assets/images/next.png");
}

@media (max-width: 576px) {
    .client_section .carousel-control-prev,
    .client_section .carousel-control-next {
        display: none;
    }
}

@media (max-width: 420px) {
    .client_section .row .col-12 {
        flex-direction: column;
    }
}

</style>
