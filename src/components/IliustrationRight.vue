
<template>

  <div class="right">
    <div class="twobox">
        <img class="top-img" src=".././assets/images/Bitmap1.png" alt="bitmap">
        <img class="bottom-img" src=".././assets/images/Path 31.png" alt="bitmap">
    </div>
    

    <div class="top-heade">
        <header>IlIustrations</header>
        <sub>the beautiful illustrations.</sub>
         <el-button circle>80</el-button>
    </div>

    <div class="bottom-boxes">
      <div class="box1">
        <div class="img-box">
          <img src=".././assets/images/Bitmap3.png" alt="bitmap">
        </div>
        <header>The Styles</header>
        <sub>Let's see how to create the kit.</sub>
        <el-button class="arrowright" type="text"></el-button>
      </div>
      <div class="box2">
        <div class="img-box">
          <img src=".././assets/images/Bitmap.png" alt="bitmap">
        </div>
        <header>The Styles</header>
        <sub>Let's see how to create the kit.</sub>
        <el-button class="arrowright" type="text"></el-button>
      </div>
    </div>

  </div>
 
</template>





<script>

  export default {
    data() {
      return {
        
        
      };
      
    },
   
    methods: {
     
    }
  }
</script>




<style>

.right{
    width: 700px;
    height: 783px;
    margin-left: 877px;
    margin-top: -115px; 
    background-color: #FFFFFF;
    box-shadow: 0px 3px 50px #0000000D;
    border-radius: 20px;

}

.right .twobox{
    width: 620px;
    height: 260px;
    background-color: #FFF6FB;
    position: relative;
    top: 55px;
    left: 40px;
    border-radius: 20px;
}

.right .twobox .top-img{
    position: relative;
    /* width: 100px; */
    left: 250px;
    height: 260px;
    z-index: 3;
}

.right .twobox .bottom-img{
    position: relative;
    /* width: 100px; */
    top: 40px;
    left: 60px;
    height: 170px;
    z-index: 1;
}

.right .top-heade{
    margin-top: 100px;
}

.right .top-heade header{
    font-family: SofiaProSemiBold;
    font-size: 30px;
    color: #252527;
    position: relative;
    left: 39px;
}


.right .top-heade sub {
    font-family: SofiaProRegular;
    position: relative;
    font-size: 75%;
    line-height: 0;
    vertical-align: baseline;
    top: -24px;
    right: -43px;
    color: #CCCBD0;
}
.right .top-heade .el-button{
  width: 50px;
  height: 50px;
  position: relative;
  top: -45px;
  left: 465px;
  background-color: #ACB2FE;
  
}

.right .top-heade .el-button span{

    font-weight: bold;
    font-size: 20px;
    color: white;

}

 .right .top-heade button:focus {
    outline: none;
  }

.right .bottom-boxes{
  margin-top: 20px;
  margin-left: 40px;
}
.right .bottom-boxes .box1{
  width: 620px;
  height: 100px;
  background-color: #FFFFFF;
  border-radius: 20px;
}




.right .bottom-boxes .img-box{
  width: 140px;
  height: 100px;
  
 background-color: #FFF6FB;
 border-radius: 20px;
}

.right .bottom-boxes .box1 .img-box img{
  
  height: 100px;
  margin-left: 45px;
}

.right .bottom-boxes .box1 header{
  font-family: SofiaProSemiBold;
  font-size: 22px;
  position: relative;
  /* left: 150px; */
  margin-left: 150px;
  top: -90px;
  color: #252527;
}

.right .bottom-boxes .box1 sub{
  font-family: SofiaProRegular;
  font-size: 14px;
  position: relative;
  left: 150px;
  top: -100px;
  color: #CCCBD0;
}

.right .bottom-boxes .box1 .arrowright{
  font-size: 10px;
  width: 20px;
  height: 30px;
  position: relative;
  background: transparent url('.././assets/images/chevron-right-2.png') 0% 0% no-repeat padding-box;
  top: -90px;
  left: 380px;

}

.right .bottom-boxes .box1 button:hover{
  margin-left: 10px;
}

.right .bottom-boxes .box1 button:focus {
    outline: none;
  }






















.right .bottom-boxes .box2{
  width: 620px;
  height: 100px;
  margin-top: 30px;
  border-radius: 20px;
  
  background-color: #FFFFFF;
  
}



.right .bottom-boxes .box2 .img-box img{
  
  height: 100px;
  margin-left: 45px;
}

.right .bottom-boxes .box2 header{
  font-family: SofiaProSemiBold;
  font-size: 22px;
  position: relative;
  margin-left: 150px;
  top: -90px;
  color: #252527;
}

.right .bottom-boxes .box2 sub{
  font-family: SofiaProRegular;
  font-size: 14px;
  position: relative;
  left: 150px;
  top: -100px;
  color: #CCCBD0;
}

.right .bottom-boxes .box2 .arrowright{
  font-size: 10px;
  width: 20px;
  height: 30px;
  position: relative;
  background: transparent url('.././assets/images/chevron-right-2.png') 0% 0% no-repeat padding-box;
  top: -90px;
  left: 380px;

}

.right .bottom-boxes .box2 button:hover{
  margin-left: 10px;
}


.right .bottom-boxes .box2 button:focus {
    outline: none;
  }




</style>



