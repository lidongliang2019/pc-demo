<template>
  <div class="container">
    <img class="bannerImage" src="../../assets/images/bannerImage.gif">

      <img class="centerTitle" src="../../assets/images/oneTitle_03.gif">
      <img class="flash" src="../../assets/images/flash_07.gif">
      <span class="twoLeftTitle">{{twoLeftTitle}}</span>
      <span class="twoRightTitle">{{twoRightTitle}}</span>
      <div class="tabsInput">
        <template>
          <el-tabs v-model="activeName" type="card" @tab-click="handleClick">
            <el-tab-pane label="用户管理" name="first">姑苏金茂悦</el-tab-pane>
            <el-tab-pane label="配置管理" name="second">金辉融侨城</el-tab-pane>
            <el-tab-pane label="角色管理" name="third">合景峰汇三期</el-tab-pane>
          </el-tabs>
        </template>
        <el-button type="primary" class="btn">
          <i class="el-icon-search"></i>
          搜索
        </el-button>
      </div>
      <input class="centerInput"></input>

  </div>
</template>

<script>
    export default {
        name: "Banner",
        data() {
            return {
                twoLeftTitle: '苏州市·源浩网',
                twoRightTitle: '新房，二手房在售',
                activeName: 'first',
                handleClick: (tab, event) => {
                    console.log(tab, event);
                }
            }
        }
    }
</script>

<style scoped>
  .container {
    position: relative;
    padding-bottom: 0;
    text-align: center;
  }

  .bannerImage {
    position: relative;
    width: 100%;
    height: 400px;
    z-index: 1;
  }

  .centerTitle {
    position: relative;
    margin-left: 100px;
    top: -290px;
    left: 50px;
    width: 500px;
    height: 50px;
    z-index: 110;
  }

  .flash {
    position:relative;
    top: -240px;
    left: -375px;
    margin: 0 auto;
    width: 14px;
    height: 20px;
    z-index: 110;
  }

  .twoLeftTitle {
    position: relative;
    top: -245px;
    left: -370px;
    color: white;
    z-index: 110;
  }

  .twoRightTitle {
    position: relative;
    top: -245px;
    left: -330px;
    color: white;
    z-index: 110;
  }

  .tabsInput {
    position: relative;
    margin: 0 auto;
    width: 300px;
    height: 100px;
    top: -190px;
    left: -285px;
    color: black;
    border: none;
    z-index: 120;
  }

  .centerInput {
    position: relative;
    top: -251px;
    left:-109px;
    width: 650px;
    height: 55px;
    font-size: 14px;
    z-index: 110;
  }

  .btn {
    position: relative;
    height: 61px;
    width: 150px;
    top: -16px;
    left: 578px;
    background-color: #fe7f35;
    border-radius: 0px;
    border: none;
  }
  .keepCenter{
    margin: 0 auto;
    text-align: center;
  }
</style>
<style>
  .el-tabs__item.is-active {
    background-color: white;
    color: #fe7f35;
  }

  .el-tabs__item:hover {
    color: #fe7f35;
  }

  .el-tabs__item {
    color: #858689;
  }

  .el-tab-pane {
    padding-top: 5px;
    margin-left: 20px;
    font-size: 14px;
    z-index: 100;
    width: auto;
    color: #858689;
  }

  .el-tabs__content {
    color: #fe7f35;
    position: absolute;
    padding: 0;
    width: auto;
  }

  .el-tabs--card > .el-tabs__header .el-tabs__nav {
    border: none;
  }

  . .el-tabs--top.el-tabs--card > .el-tabs__header .el-tabs__item:nth-child(2) {
    border: none !important;
  }

  .el-tabs__item:last-child {
    border: none !important;
  }

  .el-tabs__item:nth-child(2) {
    border: none !important;
  }
</style>
