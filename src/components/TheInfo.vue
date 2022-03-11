<template>
  <section class="info_section layout_padding">
    <div class="container">
      <div class="info_items">
        <a href="">
          <div class="item">
            <div class="img-box box-1">
              <img src="" alt="" />
            </div>
            <div class="detail-box">
              <p>Lorem Ipsum is simply dummy text</p>
            </div>
          </div>
        </a>
        <a href="">
          <div class="item">
            <div class="img-box box-2">
              <img src="" alt="" />
            </div>
            <div class="detail-box">
              <p>+02 1234567890</p>
            </div>
          </div>
        </a>
        <a href="">
          <div class="item">
            <div class="img-box box-3">
              <img src="" alt="" />
            </div>
            <div class="detail-box">
              <p>demo@gmail.com</p>
            </div>
          </div>
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.layout_padding {
  padding: 75px 0;
}

.info_section {
  background-color: #c1dcf9;
}

.info_items {
  width: 90%;
  margin: 0 auto;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.info_items .item {
  width: 200px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  text-align: center;
}

.info_items .item .img-box {
  width: 80px;
  height: 80px;
  border-radius: 100%;
  background-color: #ffffff;
  background-repeat: no-repeat;
  background-position: center;
}

.info_items .item .detail-box {
  margin-top: 25px;
  color: #fff;
}

.info_items {
  position: relative;
}

.info_items a {
  position: relative;
}

.info_items::before {
  content: "";
  position: absolute;
  top: 25%;
  width: 80%;
  height: 1px;
  background-color: #fff;
  left: 50%;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
}

.info_items .item .img-box.box-1 {
  background-image: url("../assets/images/location-blue.png");
}

.info_items .item .img-box.box-2 {
  background-image: url("../assets/images/telephone-blue.png");
}

.info_items .item .img-box.box-3 {
  background-image: url("../assets/images/envelope-blue.png");
}

.info_items .item .img-box:hover {
  background-color: #179dfb;
}

.info_items .item .img-box:hover.box-1 {
  background-image: url("../assets/images/location-white.png");
}

.info_items .item .img-box:hover.box-2 {
  background-image: url("../assets/images/telephone-white.png");
}

.info_items .item .img-box:hover.box-3 {
  background-image: url("../assets/images/envelope-white.png");
}

@media (max-width: 768px) {
  .info_section .col-md-3 {
    text-align: center;
  }

  .info_section .col-md-3:not(:nth-last-child(1)) {
    margin-bottom: 35px;
  }

  .info_items {
    flex-direction: column;
    align-items: center;
  }

  .info_items .item {
    margin: 20px 0;
  }

  .info_items::before {
    display: none;
  }
}
</style>
