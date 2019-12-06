<template>
  <div class="container">
    <div class="header-box">
      <el-row>
        <el-col :span="24">
          <div class="grid-content bg-purple-dark">
            <div class="tab-btn">
              <el-button type="text" class="navigationBtn" style="color: black;margin-left: 20px" v-for="tabButton in tabButtons">{{tabButton.tabBtn}}
              </el-button>
              <span class="pB">
                <el-dropdown>
                <span class="el-dropdown-link">
                   {{userPhone}}
                  <i class="el-icon-arrow-down el-icon--right"></i>
                </span>
                   <el-dropdown-menu slot="dropdown">
                     <el-dropdown-item>
                       <i class="el-icon-user-solid"></i>
                       安安
                     </el-dropdown-item>
                     <el-dropdown-item>账号管理</el-dropdown-item>
                     <el-dropdown-item>退出登录</el-dropdown-item>
                </el-dropdown-menu>
                 </el-dropdown>
              </span>
            </div>
          </div>
          <img class="logo-icon" src="../assets/images/yuanhao.gif">
          <div class="btn">
            <el-button class="position-bt" icon="el-icon-caret-bottom" type="text" style="color: black">{{position}}
            </el-button>
          </div>


        </el-col>
      </el-row>
    </div>
  </div>
</template>

<script>
    export default {
        name: "Header",
        data() {
            return {
                position: '苏州',
                tabButtons: [
                    {tabBtn: '首页'},
                    {tabBtn: '新房'},
                    {tabBtn: '二手房'},
                    {tabBtn: '小区'},
                    {tabBtn: 'APP下载'},
                    {tabBtn: '地图找房'},
                    {tabBtn: '商家入驻'},
                    {tabBtn: '卖房'},
                    {tabBtn: '百科'},
                    {tabBtn: '资讯'},
                    {tabBtn: '工具'},
                ],
                userPhone: "138****2428"
            }
        }
    }
</script>

<style scoped>
  .container {
    z-index: 1000;
  }

  .bg-purple-dark {
    margin: 0;
    border-bottom: 1px solid #808081;
    background-color: #ffffff;
    height: 80px;
  }

  .logo-icon {
    position: absolute;
    top: 0;
    left: 140px;
    width: 133px;
    height: 90px;
    z-index: 100;
  }

  .btn {
    position: absolute;
    color: black;
    font-size: 16px;
    top: 20px;
    left: 290px;
  }

  .tab-btn {
    line-height: 80px;
    position: relative;
    left: 430px;
    width: auto;
    overflow: hidden;
  }
  .pB{
    margin-left: 200px;
  }
  .el-dropdown-link:hover{
    color: #fe7f35;
  }
.navigationBtn:hover{
  color: #fe7f35!important;
}

</style>
