
<template>
<div  class="right-footer">
    <div class="social-network">
        <el-button class="bookmark" circle></el-button>
        <el-button class="share" circle></el-button>
        <el-button class="heart" circle></el-button>

        <el-button-group>
            <el-button disabled><i class="el-icon-back"></i></el-button>
            <el-button><i class="el-icon-right"></i></el-button>
        </el-button-group>
    </div>

</div>

 
</template>





<script>
  export default {
    data() {
      return {
        searchinput: '',
      };
    },
    methods: {
     
    }
  }
</script>

<style>

.right-footer{
    width: 700px;
    height: 50px;
    margin-left: 900px;
    margin-top: -50px; 
    background-color: transparent;
}

.right-footer .social-network{
    margin-left: -17px
}
.right-footer .social-network .el-button{
    margin-top: 11px;
    margin-left: 30px;
    border: none;
}

.right-footer .social-network button:focus {
   outline: none;
}

.right-footer .social-network .bookmark{
    width: 20px;
    height: 10px;
    background: transparent url('.././assets/images/bookmark-1.png') 0% 0% no-repeat padding-box;
    background-position: center;
}

.right-footer .social-network .share{
    width: 20px;
    height: 10px;
    background: transparent url('.././assets/images/share.png') 0% 0% no-repeat padding-box;
    background-position: center;
}

.right-footer .social-network .heart{
    width: 20px;
    height: 10px;
    background: transparent url('.././assets/images/heart-1.png') 0% 0% no-repeat padding-box;
    background-position: center;
}
.right-footer .social-network .el-button-group {
margin-left: 340px;
}

.right-footer .social-network .el-button-group .el-button {
    padding: 0;
    
}

.right-footer .social-network .el-button-group .el-button span {
    font-size: 25px;
    padding-left: 20px;
}




</style>



