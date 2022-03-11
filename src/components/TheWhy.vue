<template>
  <section class="why_section layout_padding">
    <div class="container">
      <h3 class="custom_heading">Why choose Us</h3>
      <p class="font-weight-bold">
        It is a long established fact that a reader will be distracted by the
        readable content of a page
      </p>
    </div>
    <div class="container">
      <div class="row">
        <div v-for="(why, index) in whys" :key="index" class="col-md-6">
          <div class="img_box">
            <img :src="why.Url" alt="" />
          </div>
          <div class="detail_box">
            <h5>{{why.Hea}}</h5>
            <p>
              {{why.Pra}}
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import feature1 from '../assets/images/feature-1.png'
import feature2 from '../assets/images/feature-2.png'
import feature3 from '../assets/images/feature-3.png'
import feature4 from '../assets/images/feature-4.png'
export default {
  data() {
    return {
      whys: [
        {
          "Hea": "Fast Delivery",
          "Pra": "variations of passages of Lorem Ipsum available, but the majority have suffered",
          "Url": feature1,
        },
        {
          "Hea": "Free Shiping",
          "Pra": "variations of passages of Lorem Ipsum available, but the majority have suffered",
          "Url": feature2,
        },
        {
          "Hea": "Best Quality",
          "Pra": "variations of passages of Lorem Ipsum available, but the majority have suffered",
          "Url": feature3,
        },
        {
          "Hea": "24x7 Customer support",
          "Pra": "variations of passages of Lorem Ipsum available, but the majority have suffered",
          "Url": feature4,
        },
      ],
    };
  },
};
</script>

<style>
.layout_padding {
  padding: 75px 0;
}

.custom_heading {
  text-transform: uppercase;
  font-weight: bold;
}

.why_section .row {
  padding: 35px 0;
}

.why_section .row .col-md-6 {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  margin: 25px 0;
}

.why_section .img_box {
  min-width: 125px;
  min-height: 125px;
  margin-right: 25px;
  border: 1.5px solid #e3e2e2;
  border-radius: 7px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.why_section .img_box img {
  width: 50px;
}

.why_section .detail_box h5 {
  font-weight: bold;
  color: #4b9df9;
}

@media (max-width: 576px) {
  .why_section .row .col-md-6 {
    flex-direction: column;
    text-align: center;
  }

  .why_section .img_box {
    margin-right: 0;
    margin-bottom: 20px;
  }
}
</style>
