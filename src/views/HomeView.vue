<template>
  <section class="slider_section position-relative">
    <div
      id="carouselExampleControls"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="slider_item-box">
            <div class="slider_item-container">
              <div class="container">
                <div class="row">
                  <div class="col-md-5">
                    <div class="slider_img-box">
                      <div>
                        <img src="../assets/images/watch.png" alt="" class="" />
                      </div>
                    </div>
                  </div>
                  <div class="col-md-7">
                    <div class="slider_item-detail">
                      <div>
                        <h1>Stylish watches</h1>
                        <p>
                          consectetur adipiscing elit, sed do eiusmod tempor
                          incididunt ut labore et dolore magna aliqua. Ut enim
                          ad minim veniam, quis nostrud exercitation ullamco l
                        </p>
                        <div class="d-flex">
                          <a href="" class="slider-btn1 me-3"> Read More </a>
                          <a href="" class="slider-btn2"> Contact Us </a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="slider_item-box">
            <div class="slider_item-container">
              <div class="container">
                <div class="row">
                  <div class="col-md-5">
                    <div class="slider_img-box">
                      <div>
                        <img src="../assets/images/watch.png" alt="" class="" />
                      </div>
                    </div>
                  </div>
                  <div class="col-md-7">
                    <div class="slider_item-detail">
                      <div>
                        <h1>Stylish watches</h1>
                        <p>
                          consectetur adipiscing elit, sed do eiusmod tempor
                          incididunt ut labore et dolore magna aliqua. Ut enim
                          ad minim veniam, quis nostrud exercitation ullamco l
                        </p>
                        <div class="d-flex">
                          <a href="" class="slider-btn1 me-3"> Read More </a>
                          <a href="" class="slider-btn2"> Contact Us </a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="slider_item-box">
            <div class="slider_item-container">
              <div class="container">
                <div class="row">
                  <div class="col-md-5">
                    <div class="slider_img-box">
                      <div>
                        <img src="../assets/images/watch.png" alt="" class="" />
                      </div>
                    </div>
                  </div>
                  <div class="col-md-7">
                    <div class="slider_item-detail">
                      <div>
                        <h1 class="">Stylish watches</h1>
                        <p>
                          consectetur adipiscing elit, sed do eiusmod tempor
                          incididunt ut labore et dolore magna aliqua. Ut enim
                          ad minim veniam, quis nostrud exercitation ullamco l
                        </p>
                        <div class="d-flex">
                          <a href="" class="slider-btn1 me-3"> Read More </a>
                          <a href="" class="slider-btn2"> Contact Us </a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="custom_carousel-control">
        <a
          class="carousel-control-prev"
          href="#carouselExampleControls"
          role="button"
          data-bs-slide="prev"
        >
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleControls"
          role="button"
          data-bs-slide="next"
        >
        </a>
      </div>
    </div>
  </section>
  <TheAbout />
  <TheBrand />
  <TheWhy />
  <TheClient />
  <TheContact />
  <TheInfo />
</template>

<script>
import TheAbout from "@/components/TheAbout.vue";
import TheBrand from "@/components/TheBrand.vue";
import TheWhy from "@/components/TheWhy.vue";
import TheClient from "@/components/TheClient.vue";
import TheContact from "@/components/TheContact.vue";
import TheInfo from "@/components/TheInfo.vue";
export default {
  name: "HomeView",
  components: {
    TheAbout,
    TheBrand,
    TheWhy,
    TheClient,
    TheContact,
    TheInfo
  },
};
</script>

<style scoped>
.slider_section {
  height: auto;
  background-color: #b5caee;
  padding-top: 8%;
}

.slider_item-box {
  width: 100%;
  height: 100%;
}

.slider_item-box .container {
  height: 100%;
}

.slider_img-box {
  width: 85%;
  margin: 0 auto;
}

.slider_img-box img {
  width: 100%;
}

.slider_item-container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  width: 100%;
  height: 100%;
  background-repeat: no-repeat;
}

.slider-btn1 {
  display: inline-block;
  padding: 10px 35px;
  background-color: #f2d8b9;
  border: 1px solid #f2d8b9;
  color: #ffffff;
}

.slider-btn1:hover {
  background-color: transparent;
  color: #f2d8b9;
}

.slider-btn2 {
  display: inline-block;
  padding: 10px 35px;
  background-color: #252525;
  border: 1px solid #252525;
  color: #ffffff;
}

.slider-btn2:hover {
  background-color: transparent;
  color: #252525;
}

.slider_item-detail h1 {
  font-size: 68px;
  width: 95%;
  text-transform: uppercase;
}

.slider_item-detail p {
  margin: 45px 0;
}

.slider_section #carouselExampleControls,
.carousel-inner,
.carousel-item {
  height: 100%;
}

.slider_section .carousel-control-prev,
.slider_section .carousel-control-next {
  position: absolute;
  top: 50%;
  width: 50px;
  height: 50px;
  border: none;
  border-radius: 100%;
  opacity: 1;
  background-repeat: no-repeat;
  background-size: 10px;
  background-position: center;
  background-color: #f2d8b9;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}

.slider_section .carousel-control-prev:hover,
.slider_section .carousel-control-next:hover {
  background-color: #ffffff;
}

.slider_section .carousel-control-prev {
  left: 2%;
  background-image: url("../assets/images/prev.png");
}

.slider_section .carousel-control-next {
  right: 2%;
  background-image: url("../assets/images/next.png");
}

@media (max-width: 1120px) {
  .slider_section {
    padding: 50px 0;
  }
}

@media (max-width: 768px) {
  .slider_img-box {
    width: 85%;
    margin: 65px auto;
  }

  .slider_section .custom_carousel-control {
    position: absolute;
    top: 100%;
    left: 50%;
    width: 105px;
    transform: translate(-50%, -50%);
    display: flex;
    justify-content: space-between;
  }

  .slider_img-box {
    margin-left: 20%;
  }

  .slider_section .custom_carousel-control {
    top: 106%;
  }

  .slider_section {
    padding: 50px 0 105px 0;
  }

  .slider_section .carousel-control-prev {
    left: 0;
  }

  .slider_section .carousel-control-next {
    right: 0;
  }
}

@media (max-width: 576px) {
  .slider_item-container .slider_item-detail {
    text-align: center;
  }

  .slider_item-container .slider_item-detail .d-flex {
    justify-content: center;
  }
}
</style>
