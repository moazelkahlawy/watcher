<template>
  <header class="header_section">
    <div class="container-fluid">
      <nav class="navbar navbar-expand-lg custom_nav-container pt-3">
        <router-link class="navbar-brand" to="/">
          <span> Watcher </span>
        </router-link>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <div
            class="d-flex ms-auto flex-column flex-lg-row align-items-center"
          >
            <ul class="navbar-nav">
              <li class="nav-item active">
                <router-link class="nav-link" to="/">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/about"> About </router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/watch">
                  Our Watches
                </router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/contact"
                  >Contact us</router-link
                >
              </li>
            </ul>
            <form class="form-inline my-2 my-lg-0 ms-0 ms-lg-4 mb-3 mb-lg-0">
              <button
                class="btn my-2 my-sm-0 nav_search-btn"
                type="submit"
              ></button>
            </form>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header_section .container-fluid {
  background-color: #b5caee;
  padding-right: 25px;
  padding-left: 25px;
}

.header_section .nav_container {
  margin: 0 auto;
}

.custom_nav-container.navbar-expand-lg .navbar-nav .nav-link {
  padding: 10px 30px;
  color: #ffffff;
  text-align: center;
  text-transform: uppercase;
}

.navbar-brand,
.navbar-brand:hover {
  text-transform: uppercase;
  font-weight: bold;
  font-size: 24px;
  color: #fafcfd;
}

.custom_nav-container .nav_search-btn {
  background-image: url("../assets/images/search-icon.png");
  background-size: 22px;
  background-repeat: no-repeat;
  background-position-y: 7px;
  width: 35px;
  height: 35px;
  padding: 0;
  border: none;
}

.navbar-brand {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.navbar-brand img {
  width: 45px;
  margin-right: 5px;
}

.navbar-brand span {
  font-size: 20px;
  font-weight: 700;
  color: #191919;
  margin-top: 5px;
}

.custom_nav-container {
  z-index: 99999;
  padding: 15px 0;
}

.custom_nav-container .navbar-toggler {
  outline: none;
}

.custom_nav-container .navbar-toggler .navbar-toggler-icon {
  background-image: url("../assets/images/menu.png");
  background-size: 55px;
}

.navbar-toggler:focus {
  box-shadow: none !important;
}

@media (max-width: 992px) {
  .custom_nav-container .nav_search-btn {
    background-position: center;
  }
}
</style>
