<template>
  <section class="brand_section layout_padding2">
    <div class="container">
      <div class="brand_heading">
        <h3 class="custom_heading">Our watch brands</h3>
        <p class="font-weight-bold">
          It is a long established fact that a reader will be distracted by the
          readable content of a page
        </p>
      </div>
    </div>
    <div class="container-fluid brand_item-container">
      <div class="brand_item-box">
        <div class="brand_img-box item-1">
          <a href=""> View More </a>
        </div>
        <div class="brand_detail-box">
          <h5>$<span> 40 </span></h5>
          <h6 class="">best watch</h6>
        </div>
      </div>
      <div class="brand_item-box">
        <div class="brand_img-box item-2">
          <a href=""> View More </a>
        </div>
        <div class="brand_detail-box">
          <h5>$<span> 50 </span></h5>
          <h6 class="">best watch</h6>
        </div>
      </div>
      <div class="brand_item-box">
        <div class="brand_img-box item-3">
          <a href=""> View More </a>
        </div>
        <div class="brand_detail-box">
          <h5>$<span> 60 </span></h5>
          <h6 class="">best watch</h6>
        </div>
      </div>
      <div class="brand_item-box">
        <div class="brand_img-box item-4">
          <a href=""> View More </a>
        </div>
        <div class="brand_detail-box">
          <h5>$<span> 70 </span></h5>
          <h6 class="">best watch</h6>
        </div>
      </div>
      <div class="brand_item-box">
        <div class="brand_img-box item-5">
          <a href=""> View More </a>
        </div>
        <div class="brand_detail-box">
          <h5>$<span> 80 </span></h5>
          <h6 class="">best watch</h6>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
};
</script>

<style scoped>
.layout_padding2 {
  padding: 45px 0;
}

.custom_heading {
  text-transform: uppercase;
  font-weight: bold;
}

.brand_section {
  text-align: center;
  background-color: #c1dcf9;
}

.brand_section h3 {
  color: #fcfcfc;
}

.brand_section .brand_item-container {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.brand_item-box {
  width: 265px;
  margin: 30px 10px 0 10px;
}

.brand_img-box {
  height: 310px;
  background-size: cover;
  background-position: center;
  position: relative;
}

.brand_img-box.item-1 {
  background-image: url("../assets/images/item-1.jpg");
}

.brand_img-box.item-2 {
  background-image: url("../assets/images/item-2.jpg");
}

.brand_img-box.item-3 {
  background-image: url("../assets/images/item-3.jpg");
}

.brand_img-box.item-4 {
  background-image: url("../assets/images/item-4.jpg");
}

.brand_img-box.item-5 {
  background-image: url("../assets/images/item-5.jpg");
}

.brand_img-box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  overflow: hidden;
}

.brand_img-box a {
  display: none;
  opacity: 0;
  background-color: transparent;
  border: 1px solid #999999;
  color: #f9fafa;
  padding: 12px 35px;
  font-size: 15px;
  z-index: 3;
  -webkit-transition: opacity 0.4s;
  transition: opacity 0.4s;
}

.brand_img-box::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(37, 37, 37, 0.9);
  z-index: 1;
  -webkit-transform: translateY(320px);
  transform: translateY(320px);
  -webkit-transition: -webkit-transform 0.3s;
  transition: -webkit-transform 0.3s;
  transition: transform 0.3s;
  transition: transform 0.3s, -webkit-transform 0.3s;
}

.brand_img-box:hover {
  cursor: pointer;
}

.brand_img-box:hover::before {
  -webkit-transform: translateY(0);
  transform: translateY(0);
}

.brand_img-box:hover a {
  display: inline-block;
  opacity: 1;
}

.brand_detail-box {
  margin-top: 20px;
}

.brand_detail-box h5 {
  text-transform: uppercase;
  font-weight: bold;
  color: #242425;
}

.brand_detail-box h5 span {
  color: #179dfb;
}

.brand_detail-box h6 {
  text-transform: uppercase;
  font-weight: bold;
  color: #fcf9fc;
}
</style>
