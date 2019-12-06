<template>
    <div class="container">
      <div class="headerBox">
        <img src="../../assets/images/baike_09.gif" class="baiKeIcon">
        <span style="color: #fe7f35">
          百科
        </span>
        推荐
        <br/>
        <span style="color: #b0b1b4;font-size: 18px">
          Encyclopedia Recommendation
        </span>
      </div>
      <div class="centerContent">
        <div class="leftContent">
          <img src="../../assets/images/left1_13.gif">
          <div class="position">
            <div class="title">
              购房通知
            </div>
            <span style="color: #b1b1b3">
            NOTICE
          </span>
          </div>
          <div class="listImage">
            <img  style="width: 300px; height: 160px" src="../../assets/images/listImage_23.gif">
            <div class="bottomTitle">
              宽大两房和紧凑小三房该如何选择
            </div>
          </div>
          <div class="bottomBox">
            很多刚需在卖房的时候因为经济因素……
          </div>
          <div class="moreButton">
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
          </div>
        </div>
        <div class="content">
          <img src="../../assets/images/left2_15.gif">
          <div class="position">
            <div class="title">
              购房通知
            </div>
            <span style="color: #b1b1b3">
            NOTICE
          </span>
          </div>
          <div class="listImage">
            <img  style="width: 300px; height: 160px" src="../../assets/images/listImage_23.gif">
            <div class="bottomTitle">
              宽大两房和紧凑小三房该如何选择
            </div>
          </div>
          <div class="bottomBox">
            很多刚需在卖房的时候因为经济因素……
          </div>
          <div class="moreButton">
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
          </div>
        </div>
        <div class="rightContent">
          <img src="../../assets/images/left3_17.gif">
          <div class="position">
            <div class="title">
              购房通知
            </div>
            <span style="color: #b1b1b3">
            NOTICE
          </span>
          </div>
          <div class="listImage">
            <img  style="width: 300px; height: 160px" src="../../assets/images/listImage_23.gif">
            <div class="bottomTitle">
              宽大两房和紧凑小三房该如何选择
            </div>
          </div>
          <div class="bottomBox">
            很多刚需在卖房的时候因为经济因素……
          </div>
          <div class="moreButton">
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
            <el-button class="textButton" type="text">文字按钮</el-button>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "BaiKe"
    }
</script>

<style scoped>
.container{
  position: relative;
  top: -723px;
  width: 100%;
  height: 600px;
  background-color: #f9f9f9;
}
.centerContent{
  position: relative;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  width: 1100px;
  height: 300px;
  margin: 20px auto;
}
.leftContent{
  position: relative;
  width: 300px;
  height: 100%;
}
.content{
  position: relative;
  width: 300px;
  height: 100%;
}
.rightContent{
  position: relative;
  width: 300px;
  height: 100%;
}
.baiKeIcon{
  position: relative;
  top: 5px;
}
  .headerBox{
    position: relative;
    width: 425px;
    margin: 0 auto;
    padding-top: 70px;
    font-size: 28px;
    text-align: center;
  }
  .position{
    position: relative;
    top: -50px;
    left: 75px;
  }
  .title{
    position: relative;
    border-bottom: 1px dashed #999999;
    width: 80px;
    font-size: 18px;
  }
  .listImage{
    position: relative;
    top: -10px;
    width: 200px;
  }
  .bottomTitle{
    position: absolute;
    width: 300px;
    height: 30px;
    margin: 0;
    bottom: 3px;
    background-color: #808081;
    opacity: 0.7;
    color: #ffffff;
  }
  .bottomBox{
    position: relative;
    width: 300px;
    height: 30px;
    bottom: 10px;
    background-color: #f8f8f8;
    box-shadow: 10px 10px 16px #eeeeee;
  }
  .moreButton{
    position: relative;
    width: 300px;
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    flex-wrap: wrap;
    margin-left: -5px;
  }
  .textButton{
    position: relative;
    font-size: 16px;
    margin-left: 10px;
    color: #000000;
  }
</style>
