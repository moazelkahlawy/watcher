<template>
  <section class="about_section layout_padding">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-5 offset-md-2">
          <div class="about_detail-box">
            <h3 class="custom_heading">About our watch</h3>
            <p class="">
              It is a long established fact that a reader will be distracted by
              the readable content of a page when looking at its layout. The
              point of using Lorem Ipsum is that it has a more-or-less normal
              distribution of letters, as opposed to using 'Content here,
              content here', making it
            </p>
            <div>
              <a href=""> Read More </a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="about_img-box">
            <img src="../assets/images/about.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.layout_padding {
  padding: 75px 0;
}

.about_section .row {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.custom_heading {
  text-transform: uppercase;
  font-weight: bold;
}

.about_detail-box p {
  margin-top: 30px;
  margin-bottom: 45px;
}

.about_detail-box a {
  display: inline-block;
  padding: 7px 25px;
  background-color: #252525;
  border: 1px solid #252525;
  color: #ffffff;
}

.about_detail-box a:hover {
  background-color: transparent;
  color: #252525;
}

.about_img-box img {
  width: 100%;
}

</style>
