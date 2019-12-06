<template>
  <div class="container">
    <div class="contentCenter">
      <div class="topContent">
        <img src="../../assets/images/erweima_36.gif" class="erWeiMa">
        <span class="aa">扫码下载APP</span>
        <div class="phoneNumber">
          <i class="el-icon-phone"></i>
          <span style="position:relative;top: -5px;">官方客服</span>
          <span style=";position: relative;top: -5px; margin-left: 10px">400-928-0806</span>
        </div>
        <div class="link">
          <i class="el-icon-s-promotion"></i>
          <span style="position:relative;top: -5px;">友情链接</span>
          <span style=";position: relative;top: -5px; margin-left: 20px;font-size: 14px;">
              <a href="" style="color: #8c8c8c;text-decoration:none;transition:0.5s;" class="cc" >
                迅客驿站
              </a>
            </span>
        </div>
      </div>
      <div class="content">
        <p class="title">合作城市</p>
        <div class="cityName">
          <a href="" style="color: #8c8c8c;text-decoration:none;transition:0.5s;" class="bb" v-for="item in items" :key="items">
            {{item}}
          </a>
        </div>
      </div>
      <div class="bottomContent">
        <div style="background:linear-gradient(to left,#b6b6b6,#ffffff,#b6b6b6);height:1px;margin-top: 10px;"></div>
        <div style="margin-top: 30px">
          © Copyright2019
          <a href="" class="alterA">
            苏州源浩网营销策划有限公司
          </a>
          <el-divider direction="vertical"></el-divider>
          <a href="" class="alterA">
            苏ICP备16040109号-4
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "Foot",
        data:function () {
            return{
                items:[
                    "苏州",
                    "上海",
                    "鹤岗",
                    "常熟",
                    "武汉",
                    "北京",
                    "杭州",
                    "重庆",
                    "大连",
                    "昆山",
                    "连云港",
                    "日照",
                    "威海",
                    "晋江",
                    "南通",
                    "佳木斯",
                    "三亚",
                    "成都",
                    "绵阳",
                    '九江'
                ]
            }
        }
    }
</script>

<style scoped>
  .container {
    position: relative;
    top: -554px;
    width: 100%;
    height: 450px;
    background-color: #333333;
  }

  .contentCenter {
    position: relative;
    margin: 0 auto;
    width: 1200px;
    height: 450px;
  }

  .topContent {
    position: relative;
    width: 100%;
    height: 150px;
  }

  .content {
    position: relative;
    width: 100%;
    height: 150px;
  }

  .bottomContent {
    position: relative;
    text-align: center;
    width: 100%;
    height: 150px;
    color: white;
  }

  .erWeiMa {
    position: absolute;
    top: 25px;
    left: 30px;
    width: 100px;
    height: 100px;
  }

  .el-icon-phone {
    font-size: 30px;
  }

  .el-icon-s-promotion {
    font-size: 30px;
  }

  .aa {
    position: absolute;
    bottom: 0;
    left: 30px;
  }
  .alterA{
    text-decoration:none;
    color: white;
  }
  .alterA:hover{
    color: #fe7f35!important;
  }
  .phoneNumber {
    position: absolute;
    left: 250px;
    top: 30px;
    color: #f8f8f8;
    font-size: 20px
  }

  .link {
    position: absolute;
    left: 250px;
    top: 90px;
    color: #f8f8f8;
    font-size: 20px
  }
  .bb{
    min-width: 130px;
    margin-left: 50px;
  }
  .cc:hover{
    color: #fe7f35!important;
  }
  .bb:hover {
    color: #fe7f35!important;
  }
  .content{
    position: relative;
    padding-top: 20px;
  }
  .cityName{
    position: relative;
    display: flex;
    text-align: left;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: flex-start;
    width: 100%;
    height: 130px;
    padding-left: 80px;
    padding-top: 15px;
    top: -40px;
  }
  .title{
    position: relative;
    text-align:center;
    top: -30px;
    color: white;
  }
  .title:before, .title:after {
    content: "";
    width: 40%;
    height: 0.5px;
    position: absolute;
    top: 50%;
  }
  .title:before {
    background: -webkit-linear-gradient(right, #eee , #666);
    background: -o-linear-gradient(left, #eee , #666);
    background: -moz-linear-gradient(left,#eee , #666);
    background: linear-gradient(to left, #eee , #666);
    left: 1px;
  }
  .title:after {
    background: -webkit-linear-gradient(left, #eee , #666);
    background: -o-linear-gradient(right, #eee , #666);
    background: -moz-linear-gradient(right,#eee , #666);
    background: linear-gradient(to right, #eee , #666);
    right: 1px;
  }
</style>
