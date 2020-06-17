
<template>
<div  class="center-top">
    <el-input class="search_input"
        placeholder="Search everything"
        prefix-icon="el-icon-search"
        v-model="searchinput">
    </el-input>

    
    <el-badge :value="3" class="icon">
      <a href="#"><i class="el-icon-bell"></i></a>
    </el-badge>
    
    <el-badge  class="icon">
      <a href="#"><i class="el-icon-collection-tag"></i></a>
    </el-badge>

    <el-button>New Post</el-button>
    

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
.center-top{
    padding-left: 250px;
    margin-top: 70px;
}

.center-top .el-input{
  width: 229px;
    margin-left: 40px;
    float: left;
    border-bottom: 1px solid #BEBDC3;
}
.center-top .search_input .el-input__inner
{
    border: none !important; 
}


.center-top .el-icon-search{
  color: black;
}
.center-top .el-input ::placeholder{
  font-family: SofiaProSemiBold;
  font-size: 14px;
  text-align: right;
}

.center-top .el-input input {
padding-left: 40px;
}

.center-top .icon{
  font-size: 19px;
  margin-top: 0px;
  padding-left: 15px;
}

.center-top .icon a{
  color: #252527;
}

.center-top .el-button{
  font-family: SofiaProSemiBold;
  font-size: 14px;
  border: 1px solid #BEBDC3;
  width: 145px;
  height: 42px;
  border-radius: 12px;
  margin-left: 35px;
  margin-top: 8px;
  color: #252527;
}

</style>



