<template>
<div class="container">
<img  class="AdvertisingImage" src="../assets/images/guanggaowei_06.gif">
  <div class="rightText">
    建发阳光城璞悦
    <br/>
    <span style="font-size: 12px">建发蒲悦，璞玉【相城区·渭塘】</span>
    <br/>
    <span style="color: #bdbdbe; font-size: 24px">轻松入住·快乐新家</span>
    <br/>
    <el-button class="plain">立即入驻</el-button>
  </div>
</div>
</template>

<script>
    export default {
        name: "AdvertisingSpace"
    }
</script>

<style scoped>
.container{
  position: relative;
  width: 100%;
  top:-520px
}
  .AdvertisingImage{
    position: relative;
    width: 100%;
  }
  .rightText{
    position: relative;
    top: -280px;
    left: 300px;
    text-align: center;
    font-size: 40px;
    font-weight: 200;
    color: #ce916b;
  }
  .plain{
    position: relative;
    top: 20px;
    width: 150px;
    color: #ce916b;
    border: 1px solid #ce916b;
    background-color: #25282b;
  }
</style>
