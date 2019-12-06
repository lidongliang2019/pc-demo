<template>
    <div class="container" >
      <div class="top1">
        <i class="el-icon-top"></i>
      </div>
      <div class="top2">
        我要
        <br/>
        加盟
      </div>
      <div class="top3">
        意见
        <br/>
        反馈
      </div>
      <div class="top4">
        APP
        <br/>
        下载
      </div>
    </div>
</template>

<script>
    export default {
        name: "RightBox"
    }
</script>

<style scoped>

.container{
  position: fixed;
  right: 30px;
  top: 400px;
  width:60px;
  height: 230px;
  text-align: center;
  background-color: #fe7f35;
  color: white;
  border-radius: 30px;
  z-index: 1000;
  transition: 300ms;
  transform: translateY(80px);
}
  .top1{
    position: relative;
    text-align: center;
    width: 50%;
    height: 25px;
    top: 10px;
    margin: 0 auto;
    border-bottom: 1px solid white;
  }
  .top2{
    position: relative;
    top:20px;
    width: 50%;
    height: 45px;
    margin: 0 auto;
    font-size: 13px;
    border-bottom: 1px solid white;
  }
  .top3{
    position: relative;
    top:30px;
    width: 50%;
    height: 45px;
    margin: 0 auto;
    font-size: 13px;
    border-bottom: 1px solid white;
  }
  .top4{
    position: relative;
    top:40px;
    width: 50%;
    height: 40px;
    margin: 0 auto;
    font-size: 13px;
    border-bottom: 1px solid white;
  }
</style>
