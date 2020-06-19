
<template>
  <div class="center">
    <header>Design Resources</header>

    <el-select v-model="value" placeholder="This Week">
      <el-option v-for="item in options" :key="item.value" :label="item.label" :value="item.value"></el-option>
    </el-select>

    <el-card class="box-card-1">
      <div>
        <el-button type="text">
          Typography
          <i class="el-icon-arrow-right"></i>
        </el-button>
        <el-progress :percentage="50"></el-progress>
        <p>The type scale is a combination of thirteen styles that are supported by the type system</p>
      </div>
      <span class="dot"></span>
      <span class="dot2"></span>
      <div>
        <i class="text1">Aa</i>
        <i class="text2">
          01/
          <span style="color:#BEBDC3">04</span>
        </i>
      </div>
    </el-card>

    <el-card class="box-card-2">
      <div>
        <el-button type="text">
          IlIustration
          <i class="el-icon-arrow-right"></i>
        </el-button>
        <el-progress :percentage="50"></el-progress>
        <div class="text1">
          <i>
            01/
            <span style="color:#BEBDC3">04</span>
          </i>
        </div>
        <div class="text2">
          <i>The beautiful IlIstration</i>
        </div>

        <div class="twoimage">
          <img class="img1" src=".././assets/images/Path30.png" alt="Path30" />
          <img class="img2" src=".././assets/images/Bitmap.png" alt="bitmap" />
        </div>
      </div>
    </el-card>

    <el-card class="box-card-3">
      <div>
        <el-button type="text">
          Guidebook
          <i class="el-icon-arrow-right"></i>
        </el-button>
        <el-progress :percentage="50"></el-progress>
        <div class="text1">
          <i>01</i>
        </div>
        <div class="text2">
          <i>The type scale is a combination of thirteen styles.</i>
        </div>
        <el-button class="arrowright" type="text"></el-button>
      </div>
    </el-card>

    <el-card class="box-card-4">
      <div>
        <el-button type="text">
          Typography
          <i class="el-icon-arrow-right"></i>
        </el-button>
        <el-progress :percentage="50"></el-progress>
      </div>

      <div class="textbold">
        <i class="text1">Semi</i>
        <br />
        <i class="text2">Bold</i>
        <br />
        <i class="text3">Type</i>
        <br />
      </div>
    </el-card>
  </div>
</template>





<script>
export default {
  data() {
    return {
      options: [
        {
          value: "Option1",
          label: "This Week"
        },
        {
          value: "Option2",
          label: "Option2"
        },
        {
          value: "Option3",
          label: "Option3"
        },
        {
          value: "Option4",
          label: "Option4"
        },
        {
          value: "Option5",
          label: "Option5"
        }
      ],
      value: ""
    };
  },

  methods: {}
};
</script>




<style>
.center {
  width: 577px;
  height: 100%;
  margin-left: 300px;
  margin-top: -7px;
}

.center header {
  font-family: SofiaProSemiBold;
  font-size: 28px;
  margin-left: 30px;
  margin-top: 44px;
  color: #252527;
  float: left;
}

.center .el-input__inner {
  font-family: SofiaProSemiBold;
  text-align: center;
  width: 145px;
  height: 43px;
  margin-left: 115px;
  margin-top: 38px;
  border-radius: 12px;
  background-color: #f8f8f8;
  border: 1px solid #f8f8f8;
}

.center .el-input__suffix {
  margin-top: 20px;
  color: #252527;
}
.el-select .el-input .el-select__caret {
  color: #252527 !important;
  text-align: center;
}

.center .el-input__inner::placeholder {
  color: #252527;
}

.center .el-card__body {
  padding: 15px;
}

.center .box-card-1 {
  float: left;
  position: absolute;
  width: 220px;
  height: 320px;
  margin-top: 56px;
  margin-left: 50px;
  border-radius: 12px;
  opacity: 1;
  background: #fff4f2 0% 0% no-repeat padding-box;
}

.center .box-card-1 .el-button {
  font-family: SofiaProSemiBold;
  font-size: 16px;
  margin-top: 14px;
  text-align: left;
  width: 100%;
  color: #f7523e;
}
.center .box-card-1 button:focus {
  outline: none;
}
.center .box-card-1 button:hover {
  margin-left: 5%;
}

.center .box-card-1 i {
  color: black;
  padding-left: 70px;
}

.center .box-card-1 .el-progress-bar {
  padding: 0;
  margin-top: -10px;
}

.center .box-card-1 .el-progress-bar__inner {
  background: transparent linear-gradient(90deg, #b7b8fc1a 0%, #fa6b5e 100%) 0%
    0% no-repeat padding-box;
}

.center .box-card-1 .el-progress__text {
  display: none;
}
.center .box-card-1 .el-progress-bar__outer {
  height: 4px !important;
}

.center .box-card-1 p {
  font-family: SofiaProRegular;
  font-size: 13px;
}

.center .box-card-1 .dot {
  height: 30px;
  width: 30px;
  margin-top: -5px;
  border-radius: 50%;
  background-color: #ffffff !important;
  display: inline-block;
  background: transparent url(".././assets/images/format-color.png") 0% 0%
    no-repeat;
  background-position: center;
}

.center .box-card-1 .dot2 {
  height: 30px;
  width: 30px;
  margin-top: -5px;
  margin-left: 5px;
  border-radius: 50%;
  background-color: #fed1cb !important;
  display: inline-block;
  background: transparent url(".././assets/images/font-spacing.png") 0% 0%
    no-repeat;
  background-position: center;
}

.center .box-card-1 .text1 {
  font-family: SofiaProRegular;
  font-size: 92px;
  font-style: normal;
  padding: 0;
  color: #f7523e;
}

.center .box-card-1 .text2 {
  font-family: SofiaProRegular;
  font-style: normal;
  font-size: 14px;
  padding: 0;
  position: absolute;
  margin-left: 52px;
  margin-top: 60px;
  color: #f7523e;
  display: inline-block;
  transform: rotate(-90deg);
}

.center .box-card-2 {
  position: absolute;
  width: 220px;
  height: 320px;
  margin-top: 56px;
  margin-left: 300px;
  border-radius: 12px;
  float: right;
  opacity: 1;
  background: #ffffff 0% 0% no-repeat padding-box;
}
.center .box-card-2 .el-button {
  font-family: SofiaProSemiBold;
  font-size: 16px;
  margin-top: 14px;
  text-align: left;
  width: 100%;
  color: #6657bb;
}
.center .box-card-2 button:focus {
  outline: none;
}
.center .box-card-2 button:hover {
  margin-left: 5%;
}

.center .box-card-2 i {
  color: black;
  padding-left: 70px;
}

.center .box-card-2 .el-progress-bar {
  padding: 0;
  margin-top: -10px;
}

.center .box-card-2 .el-progress-bar__inner {
  background: transparent linear-gradient(90deg, #b7b8fc1a 0%, #ceadff 100%) 0%
    0% no-repeat padding-box;
}

.center .box-card-2 .el-progress__text {
  display: none;
}
.center .box-card-2 .el-progress-bar__outer {
  height: 4px !important;
}

.center .box-card-2 .text1 {
  float: left;
}
.center .box-card-2 .text1 i {
  font-family: SofiaProRegular;
  font-size: 15px;
  font-style: normal;
  padding: 0;
  color: #6657bb;
}
.center .box-card-2 .text2 {
  font-family: SofiaProRegular;
  font-size: 15px;
  font-style: normal;
  width: 126px;
  margin-left: 100px;
  padding: 0;
  color: #f7523e;
}

.center .box-card-2 .text2 i {
  font-family: SofiaProRegular;
  font-size: 14px;

  font-style: normal;
  padding: 0;
  color: #bebdc3;
}

.center .box-card-2 .twoimage {
  position: absolute;
  top: 157px;
  left: 25px;
}

.center .box-card-2 .twoimage .img1 {
  z-index: 1;
  width: 170px;
}

.center .box-card-2 .twoimage .img2 {
  height: 143px;
  position: relative;
  z-index: 3;
  top: -153px;
  left: 55px;
}

.center .box-card-3 {
  float: left;
  position: absolute;
  width: 220px;
  height: 320px;
  margin-top: 402px;
  margin-left: 50px;
  border-radius: 12px;
  opacity: 1;
  background: #edf4fa 0% 0% no-repeat padding-box;
}

.center .box-card-3 .el-button {
  font-family: SofiaProSemiBold;
  font-size: 16px;
  margin-top: 22px;
  text-align: left;
  width: 100%;
  color: #65609b;
}
.center .box-card-3 button:focus {
  outline: none;
}
.center .box-card-3 button:hover {
  margin-left: 5%;
}

.center .box-card-3 i {
  color: black;
  padding-left: 70px;
}

.center .box-card-3 .el-progress-bar {
  padding: 0;
  margin-top: -10px;
}

.center .box-card-3 .el-progress-bar__inner {
  background: transparent linear-gradient(90deg, #b7b8fc1a 0%, #ceadff 100%) 0%
    0% no-repeat padding-box;
}

.center .box-card-3 .el-progress__text {
  display: none;
}

.center .box-card-3 .el-progress-bar__outer {
  height: 4px !important;
}

.center .box-card-3 .text1 {
  float: left;
  margin-top: 28px;
}
.center .box-card-3 .text1 i {
  font-family: SofiaProRegular;
  font-weight: bold;
  font-size: 50px;
  font-style: normal;
  padding: 0;
  color: #6657bb;
}
.center .box-card-3 .text2 {
  font-family: SofiaProRegular;
  font-style: normal;
  width: 126px;
  margin-left: 70px;
  margin-top: 30px;
  padding: 0;
}

.center .box-card-3 .text2 i {
  font-family: SofiaProSemiBold;
  font-size: 13px;
  font-style: normal;
  padding: 0;
  color: #938dbc;
}

.center .box-card-3 .arrowright {
  /* width: 30px; */
  margin-top: 40px;
  margin-left: 80px;
  background: transparent url(".././assets/images/arrow-right.png") 0% 0%
    no-repeat padding-box;
}

.center .box-card-3 .arrowright:hover {
  transition: 0.4s;
  margin-left: 90px;
}

.center .box-card-4 {
  position: absolute;
  width: 220px;
  height: 320px;
  margin-top: 402px;
  margin-left: 300px;
  border-radius: 12px;
  float: right;
  opacity: 1;
  background: #574bb7 0% 0% no-repeat padding-box;
}

.center .box-card-4 .el-button {
  font-family: SofiaProSemiBold;
  font-size: 16px;
  margin-top: 22px;
  text-align: left;
  width: 100%;
  color: #ffffff;
}
.center .box-card-4 button:focus {
  outline: none;
}
.center .box-card-4 button:hover {
  margin-left: 5%;
}

.center .box-card-4 i {
  color: #ffffff;
  padding-left: 70px;
}

.center .box-card-4 .el-progress-bar {
  padding: 0;
  margin-top: -10px;
}

.center .box-card-4 .el-progress-bar__inner {
  background: transparent linear-gradient(90deg, #f76e651a 0%, #fa6b5e 100%) 0%
    0% no-repeat padding-box;
}

.center .box-card-4 .el-progress__text {
  display: none;
}

.center .box-card-4 .el-progress-bar__outer {
  height: 4px !important;
  /* position: absolute; */
}

.center .box-card-4 .textbold .text1 {
  font-family: SofiaProSemiBold;
  font-style: normal;
  font-size: 65px;
  padding-left: 15px;
  color: #ffffff38;
}
.center .box-card-4 .textbold .text2 {
  font-family: SofiaProSemiBold;
  font-style: normal;
  position: relative;
  font-size: 65px;
  padding-left: 15px;
  top: -60px;
}
.center .box-card-4 .textbold .text3 {
  font-family: SofiaProSemiBold;
  font-style: normal;
  position: relative;
  font-size: 65px;
  padding-left: 15px;
  top: -112px;
  color: #ffffff38;
}
</style>



