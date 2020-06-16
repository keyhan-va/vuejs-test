
<template>
<div>
    <b-sidebar class="sidebar" aria-label="Sidebar with custom footer" no-close-on-esc  visible  no-header no-slide>
        <header>Laravel</header>
        <br>
        <ul>
            <li><a href="#">Resources <b-icon icon="fullscreen"></b-icon></a></li>
            <li><a href="#">Starred <b-icon icon="heart"></b-icon></a></li>
            <li><a href="#">Saved <b-icon icon="folder"></b-icon></a></li>
            <li><a href="#">messages <b-icon icon="heart"></b-icon></a></li>
        </ul>

        <img  class="pro-account" alt="Vue logo" src=".././assets/backpack.png">
        
        <br>
        <div class="pro-account-text">
            <i >Pro account is more <br class="pro-account-text"> Powerful Get 30% off</i>
        </div>
        
        <br>
        <b-button class="btn" >Get Pro</b-button>
        <br>

        <div class="sidebar-footer">
          <div class="footer-image">
          </div>
          <div class="footer-text">
             <i>Laravel Daily </i>
          </div>
        </div>
        
    </b-sidebar>
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
*{

    
    margin-top: 60px;
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
}

.sidebar .bg-light {
  position: fixed;
  left: 0;
  width: 255px;
  height: 100%;
  background-color: #fff !important;
  border-right: solid 1.5px rgba(136, 136, 136, 0.137); 
}

.sidebar header{
  font-size: 18px;
  text-align: left;
  padding-left: 35px;
  margin-top: 65px;
  user-select: none;
  
  
}



.sidebar ul a{
  font-size: 11px !important;
  font-weight: bold;
  /* color: rgb(189, 189, 189); */
  color: rgb(160, 160, 160);
  text-align: left;
  float: left;
  height: 100%;
  width: 100%;
  line-height: 52px;
  font-size: 20px;
  padding-left: 35px;
  box-sizing: border-box;
  transition: .4s;
 
}

ul li:hover a{
  padding-left: 50px;
  text-decoration: none;
}

ul li:active a{
    color: rgb(0, 0, 0);
}
.sidebar ul li .b-icon{
    float: right;
    margin-top: 23px;
    margin-right: 45px;
}


.sidebar .pro-account{
   
    margin: 24px 0 19px 70px;
    padding: 22px;
    width: 90px;
    height: 95px; 
    background-color: rgb(255, 241, 253);
    border-radius: 10px;
}

.sidebar .pro-account-text{
    
    font-size: 10px;
    margin-left: 70px;
}

.sidebar .btn{
    font-size: 10px;
    border-radius: 8px;
    margin-left: 60px;
    /* margin-top: 10px; */
    color: #fff;
    background-color: #5B4DBE;
    width: 125px;
    height: 36px;
} 

.sidebar .sidebar-footer{
  height:40px;
  width:100%;
  position:absolute;
  bottom:0;
  

  
}

.sidebar .sidebar-footer .footer-image{
  /* padding: 2px; */
  float: left;
  width: 22px;
  height: 22px;
  color: #5B4DBE;
  margin-left: 83px;
 background-color: #5B4DBE;
    border-radius: 50%;
    background-image: url(.././assets/shield.png);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 14px;
}

.sidebar .sidebar-footer .footer-text{
  font-size: 10px;
  margin-top: -3px;
  margin-left: 5px;
  float: left;
  color: #444446;

}



</style>



