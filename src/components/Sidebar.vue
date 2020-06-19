
<template>
  <div>
    <b-sidebar class="sidebar" no-close-on-esc visible no-header no-slide>
      <header>Laravel</header>
      <div class="rectangle"></div>

      <br />
      <ul>
        <li>
          <a href="#">
            Resources
            <b-icon icon="fullscreen"></b-icon>
          </a>
        </li>
        <li>
          <a href="#">
            Starred
            <b-icon icon="heart"></b-icon>
          </a>
        </li>
        <li>
          <a href="#">
            Saved
            <b-icon icon="folder"></b-icon>
          </a>
        </li>
        <li>
          <a href="#">
            messages
            <b-icon icon="heart"></b-icon>
          </a>
        </li>
      </ul>
      <img class="pro-account" alt="Vue logo" src=".././assets/images/backpack.png" />
      <br />
      <div class="pro-account-text">
        <i>
          Pro account is more
          <br class="pro-account-text" />Powerful Get 30% off
        </i>
      </div>
      <br />
      <b-button class="btn">Get Pro</b-button>
      <br />
      <div class="sidebar-footer">
        <b-img :src="require('.././assets/images/shield.svg')" rounded="circle" alt="Circle image"></b-img>
        <header>Laravel Daily</header>
        <li>Laravel Newsletter</li>
      </div>
    </b-sidebar>
  </div>
</template>





<script>
export default {
  data() {
    return {};
  },
  methods: {}
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  list-style: none;
  text-decoration: none;
}

.sidebar .bg-light {
  position: fixed;
  left: 0;
  width: 300px;
  height: 100%;
  background-color: #fff !important;
  border-right: solid 1.5px rgba(136, 136, 136, 0.137);
}

.sidebar header {
  font-family: SofiaProBlack;
  font-size: 24px;
  width: 84px;
  height: 24px;
  line-height: 29px;
  color: #707070;
  text-align: left;
  margin-left: 35px;
  margin-top: 80px;
  margin-bottom: 40px;
  opacity: 1;
  user-select: none;
  float: left;
}

.sidebar .rectangle {
  margin-top: 95px;
  margin-left: 123px;
  height: 4px;
  width: 15px;
  background-color: rgb(255, 6, 6);
}

.sidebar ul a {
  font-family: SofiaProSemiBold;
  font-size: 14px !important;
  color: #bebdc3;
  text-align: left;
  float: left;
  height: 100%;
  width: 100%;
  line-height: 56px;
  font-size: 20px;
  padding-left: 35px;
  box-sizing: border-box;
  transition: 0.4s;
}

ul li:hover a {
  font-size: 14px !important;
  padding-left: 50px;
  text-decoration: none;
}

ul li:active a {
  color: #707070;
}
.sidebar ul li .b-icon {
  float: right;
  margin-top: 20px;
  margin-right: 45px;
}

.sidebar .pro-account {
  margin: 33px 0 19px 70px;
  padding: 25px;
  width: 105px;
  height: 110px;
  background-color: rgb(255, 241, 253);
  border-radius: 10px;
}

.sidebar .pro-account-text {
  font-family: SofiaProSemiBold;
  font-size: 12px;
  /* width: 160px;
  height: 49px; */

  margin-left: 60px;
  letter-spacing: 0px;
  color: #bebdc3;
}

.sidebar .btn {
  font-family: SofiaProSemiBold;
  font-size: 14px;
  border-radius: 12px;
  margin-left: 40px;
  /* margin-top: 10px; */
  color: #fff;
  background-color: #5b4dbe;
  width: 150px;
  height: 42px;
}

.sidebar .sidebar-footer img {
  margin-left: 100px;
  margin-top: 220px;
  padding: 4px;
  background-color: #5b4dbe;
  width: 30px;
  height: 30px;
}

.sidebar .sidebar-footer header {
  font-family: SofiaProSemiBold;
  color: #707070;
  width: 100px;
  font-size: 10px;
  padding: 0;
  margin: -38px 0 0 135px;
}

.sidebar .sidebar-footer li {
  font-family: SofiaProSemiBold;
  width: 100px;
  font-style: normal;
  color: #bebdc3;
  font-size: 10px;
  margin: -21px 0 0 135px;
}
</style>



