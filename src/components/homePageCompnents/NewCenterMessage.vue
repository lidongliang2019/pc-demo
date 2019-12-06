<template>
<div class="container">
<HeaderTitle></HeaderTitle>
<div class="centerContent">
<div class="textCenter" v-for="item in lists" :key="item">
<img src="../../assets/images/xinwen_30.gif">
  <h2 class="title">卖房一般需要什么流程？</h2>
    <i class="el-icon-document"></i>
    <p class="textDetails">房管局网签是什么意思？卖房的整个流程与买方付款方式相关，全程流程相对于贷款……</p>
  <p class="bottomDate">2019-12-31</p>
</div>
  </div>
</div>
</template>

<script>
  import HeaderTitle from "../Common/HeaderTitle";
    export default {
        name: "NewCenterMessage",
        components: {HeaderTitle},
        data:function () {
            return{
                lists:[
                    '1',
                    '2',
                    '3',
                    '4',
                    '5',
                    '6'
                ]
            }
        }
    }
</script>

<style scoped>
.container{
  position: relative;
  width: 100%;
  height: auto;
  top: -380px;
}
.centerContent{
  position: relative;
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  flex-wrap: wrap;
  width: 1250px;
  height: 300px;
  top: -360px;
  margin: 0 auto;

}
  /*.container >>> .headerBox {*/
  /*}*/
  .textCenter{
    position: relative;
    width: 550px;
    height: 116px;
    margin-bottom: 30px;
  }
  .textCenter:hover{
    border-radius: 5px;
    box-shadow: 5px 5px 10px #DCDCDC;
  }
  .title{
    position: absolute;
    top: -20px;
    left: 170px;
  }
  .el-icon-document{
    position: absolute;
    top: 40px;
    left: 170px;
  }
  .textDetails{
    position: absolute;
    top: 20px;
    left: 195px;
    color: #8c8c8c;
  }
  .bottomDate{
    position: absolute;
    top: 75px;
    left: 195px;
    color: #8c8c8c;
  }
</style>
