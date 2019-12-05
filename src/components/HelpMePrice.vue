<template>
    <div class="container">
      <img src="../assets/images/homesafatu_33.gif" class="backgroundImage">
      <div class="dataInput">
        <el-input class="oneInput" placeholder="填写购买房子所在的小区名称"></el-input>
        <div class="twoInputs">
          <div>
            楼栋
            <el-input class="twoInput"></el-input>
          </div>
          <div>
            房间
            <el-input class="twoInput"></el-input>
          </div>
          <div>
            面积
            <el-input class="twoInput"></el-input>
          </div>
          <div>
            价格
            <el-input class="twoInput"></el-input>
          </div>
        </div>
        <el-input class="threeInput" placeholder="填写您的手机号"></el-input>
        <el-button class="helpBtn" type="primary" round>立即帮我谈价</el-button>
      </div>
    </div>
</template>

<script>
    export default {
        name: "HelpMePrice",
        data:function(){
            return{
                from:{
                    name:''
                }
            }
        }
    }
</script>

<style scoped>
.container{
  position: relative;
  width: 100%;
  top: -550px;
}
  .backgroundImage{
    width: 100%;
  }
  .dataInput{
    position: absolute;
    top: 30px;
    left: 900px;
    width: 400px;
    height: 370px;
    text-align: center;
    background-color: #1f2221;
  }
  .oneInput{
    position: relative;
    padding-left: 40px;
    top: 50px;
    width: 250px;
    margin: 0 auto;
    background-color: #3a3d47;
  }
  .twoInputs{
    position: relative;
    text-align: left;
    display: flex;
    margin-left: 60px;
    top: 80px;
    width: 300px;
    justify-content: space-between;
    color: #f8f8f8;
  }
  .twoInput{
    text-align: left;
    width: 60px;
  }
  .threeInput{
    position: relative;
    padding-left: 90px;
    top: 120px;
    width: 210px;
    margin: 0 auto;
    background-color: #3a3d47;
  }
  .helpBtn{
    position: relative;
    top: 150px;
    width: 170px;
    height: 45px;
    background-color: #fe7f35;
    border: none;
  }
</style>
<style>
  .el-input__inner{
    background-color: #3a3d47;
    border-radius: 0;
    border: none;
  }

</style>
