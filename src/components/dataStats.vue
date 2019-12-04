<template>
  <div class="container">
    <img class="blackImage" src="../assets/images/diTu_02.gif">
    <div class="dataDisplay">
      <div class="left1">
        <p class="icon-top">
        <span style="color: #fe7f35">
          “
        </span>
          <br/>
          5144
        </p>
        <br/>
        <p class="textState">
          苏州<span style="color: #fe7f35">本月</span>二手房参考<br/>均价 （元/㎡）
        </p>
        <img src="../assets/images/bingtu_04.gif" class="cakeIcon">
      </div>
      <div class="left2">
        <p class="icon-top">
        <span style="color: #fe7f35">
          “
        </span>
          <br/>
          14214
        </p>
        <br/>
        <p class="textState">
          苏州<span style="color: #fe7f35">本月</span>二手房房源<br/>挂牌均价 （元/㎡）
        </p>
        <img src="../assets/images/zhutu_06.gif" class="cakeIcon">
      </div>
      <div class="left3">
        <p class="icon-top">
        <span style="color: #fe7f35">
          “
        </span>
          <br/>
          514
        </p>
        <br/>
        <p class="textState">
          苏州<span style="color: #fe7f35">今日</span>新增客房<br/>比例
        </p>
        <img src="../assets/images/zhexiantu_08.gif" class="cakeIcon">
      </div>
    </div>

  </div>
</template>

<script>
    export default {
        name: "dataStats"
    }
</script>

<style scoped>
  .container{
    position: relative;
    height: auto;
    margin: 0;
    top: -415px;
  }
  .blackImage {
    position: relative;
    height: auto;
    width: 100%;
  }

  .dataDisplay {
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    top: -250px;
    width: 1000px;
    height: 200px;
    margin: 0 auto;
  }

  .left1 {
    width: 300px;
    height: 100%;
    font-size: 15px;
    color: #b8b8b9;
    background-color: #000000;
    border: 1px dashed #fe7f35;
  }

  .left2 {
    width: 300px;
    height: 100%;
    font-size: 15px;
    color: #b8b8b9;
    background-color: #000000;
    border: 1px dashed #fe7f35;
  }

  .left3 {
    width: 300px;
    height: 100%;
    font-size: 15px;
    color: #b8b8b9;
    background-color: #000000;
    border: 1px dashed #fe7f35;
  }

  .icon-top {
    position: relative;
    margin: 30px auto 0 30px;
    width: 20px;
    font-size: 35px;
  }

  .textState {
    position: relative;
    top: -10px;
    left: 30px;
  }

  .cakeIcon {
    position: relative;
    float: right;
    top: -100px;
    right: 25px;
  }
</style>
