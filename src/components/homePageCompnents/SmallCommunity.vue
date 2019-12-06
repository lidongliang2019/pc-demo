<template>
  <div class="container">
    <div class="keepCenter">
      <div class="leftText">
        小区
        <span style="font-size: 20px;color:#999999">为您推荐</span>
      </div>

      <div class="leftBox">
        <div class="topText">
          建发阳光城蒲悦<br/>
          <span style="font-size: 12px">建发阳光城蒲悦【相城区·渭塘】</span>
        </div>
        <div class="twoTitle">
          1.2万/平
          <br/>
          <span class="bottomText">
            2018
          <el-divider direction="vertical"></el-divider>
          住宅
          <el-divider direction="vertical"></el-divider>
          359户
          </span>
        </div>
        <div class="btnButton">
          <div class="leftBtn">
            <el-button class="el-icon-back"></el-button>
          </div>
          <div class="rightBtn">
            <el-button class="el-icon-right" ></el-button>
          </div>
        </div>

      </div>
      <div class="rightImage">
        <img src="../../assets/images/xiaoqutu_03.gif">
      </div>
    </div>


  </div>

</template>

<script>
    export default {
        name: "SmallCommunity"
    }
</script>

<style scoped>
  .container {
    position: relative;
    top: -653px;
    width: 100%;
    height: 300px;
    padding-top: 40px;
    background-color: #f8f8f8;
  }
  .keepCenter{
    position: relative;
    width: 1280px;
    height: auto;
    margin: 0 auto;
  }
  .leftText {
    position: relative;
    font-weight: 600;
    color: #fe7f35;
    font-size: 36px;

  }

  .leftBox {
    position: relative;
    top: 20px;
    left: 20px;
    width: 280px;
    height: 220px;
    background-color: #fe7f35;
    color: white;
    font-size: 23px;
    z-index: 100;
    box-shadow: 0 5px 15px #fe7f35;
  }

  .topText {
    position: relative;
    top: 20px;
    left: 20px;
  }

  .leftText {
    position: relative;
    top: 0;
    left: 0;
    padding-left: 20px;
  }

  .twoTitle {
    position: relative;
    top: 40px;
    left: 20px;
    font-size: 23px;
  }

  .bottomText {
    font-size: 14px;
  }

  .btnButton {
    width: 100%;
    height: 30px;
    display: flex;
    flex-direction: row;
    font-size: 20px;
    justify-content: space-around;
    position: relative;
    top: 67px;
  }

  .el-icon-back {
    position: relative;
    width: 140px;
    height: auto;
    border-radius:0;
    border: none;
    color: #f8f8f8;
    background-color: #fe7f35;
  }

  .el-icon-right {
    position: relative;
    width: 140px;
    height: auto;
    border-radius:0;
    border: none;
    color: #f8f8f8;
    background-color: #fe7f35;
  }
  .rightImage{
    position: relative;
    top: -280px;
    left: 250px;
    z-index: 1;
    transition: all.6s;
  }
  .rightImage:hover{
    transform: scale(1.05);
  }
</style>
