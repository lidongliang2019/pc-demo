<template>
  <div class="container">
    <!--<div id="app" v-show="false">-->
    <!--  <button @click='concat'>concat</button>-->
    <!--&lt;!&ndash;  尾部添加&ndash;&gt;-->
    <!--  <button @click="pop">pop</button>-->
    <!--&lt;!&ndash;  尾部删除&ndash;&gt;-->
    <!--  <button @click="shift">shift</button>-->
    <!--&lt;!&ndash;  头部删除&ndash;&gt;-->
    <!--  <button @click="unshift">unshift</button>-->
    <!--&lt;!&ndash;  头部添加&ndash;&gt;-->
    <!--</div>-->
    <!--  <ul v-show="false">-->
    <!--    <li v-for="item in items" >-->
    <!--      {{ item }}-->
    <!--    </li>-->
    <!--  </ul>-->
    <div class="headTitle">
      <p style="color: #fe7f35;font-size:20px;font-weight: 600;letter-spacing: 3px">
    <span>
      <img src="../assets/images/loufangIcon_11.gif" class="houseIcon">
    </span>
        新房<span style="color: black">首推</span>
      </p>
      <h5 style="color: #808081">New House Frist Promotion</h5>
    </div>

    <div class="newHouseBox" v-for="item in items">
      <div class="newHouseDetail">
        <div class="topContent">
          <p class="newHouseName">
            宁宇家园
            <span style="font-size: small;font-weight: 300">
                2003年
              </span>
          </p>
          <div>
            <span>
            <i class="el-icon-map-location">
                [津南.八里台] 天嘉湖大道西侧
            </i>
            </span>
          </div>
          <div class="rightPrice" style="color: red">
           <span style="font-size: 30px;font-weight:600;font-family: 'Agency FB';">
              2.6
           </span>
            万/平起
          </div>
        </div>
                <div class="imaginaryLine"></div>
        <div class="content">
          <p class="leftTop">
            120㎡
            <el-divider direction="vertical"></el-divider>
            <span style="font-size: 15px">
                3室/2厅/2卫
              </span>
          </p>
          <div>
            <span>
              <el-tag class="labelData" size="small">标签一</el-tag>
              <el-tag type="success" size="small">标签二</el-tag>
              <el-tag type="info" size="small">标签三</el-tag>
            </span>
          </div>
          <div class="rightPhoto">
            <div class="demo-type">
              <div>
                <el-avatar src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"></el-avatar>
              </div>
            </div>
            这里咨询
          </div>
        </div>
        <div class="imaginaryLine"></div>
        <div class="bottomContent">
             <div class="leftB">
            <div>
              最新开盘
              <span>
              2019-05-01
            </span>
            </div>
            <div>
              交房时间
              <span>
              2019-12-01
            </span>
            </div>
          </div>

          <div class="applyTime">
            看房报名中
            <span>686人已报名</span>
            <div style="font-size: 17px;font-weight: 600;margin-top: 5px;">
              18天2时19分40秒
            </div>
          </div>
          <el-button class="applyBt" type="primary">报名看房</el-button>
        </div>
      </div>
      <div class="imageBox">
        <img src="../assets/images/huxingtu_15.gif" class="newHouseImages">
      </div>
    </div>
  </div>
</template>

<script>
  import NewHouses from "./NewHouses";
    export default {
        name: "IndexNewHouse",
        data() {
            return {
                items: ['Foo', 'Bar',"da"],
                addValue: 'match',
                headValue: '1231',
            }
        },
        methods: {
            concat() {
                this.items = this.items.concat(this.addValue)
            },
            pop() {
                this.items.pop()
            },
            shift() {
                this.items.shift()
            },
            unshift() {
                this.items.unshift(this.headValue)
            }
        }
    }
</script>

<style scoped>
  .container {
    position: relative;
    width: 100%;
    height: auto;
    top: -200px;
    background-color: #f8f8f8;
  }
  .houseIcon {
    width: 20px;
    height: 25px;
  }

  .headTitle {
    width: auto;
    margin: 30px auto;
    text-align: center;
    line-height: 0;
  }

  .newHouseBox {
    position: relative;
    margin: 50px auto;
    width: 1000px;
    height: 300px;
    background-color: #f8f8f8;
    z-index: 100;
  }

  .newHouseImages {
    width: 250px;
    height: 300px;
    box-shadow: 15px 15px 20px #ebebeb;
  }

  .newHouseDetail {
    position: absolute;
    left: 250px;
    padding-left: 40px;
    bottom: 0;
    width: 710px;
    height: 250px;
    background-color: #ffffff;
    box-shadow: 10px 10px 20px #ebebeb;
  }

  .newHouseName {
    font-size: 24px;
    line-height: 0px;
    font-weight: 600;
    margin-left: 5px;
  }

  .rightPrice {
    color: red;
    position: absolute;
    right: 30px;
    top: 20px;
  }

  .imaginaryLine {
    position: relative;
    width: 680px;
    height: 30px;
    top: -15px;
    border-bottom: 1px solid #e5e5e5;
  }

  .content {
    width: 100%;
    height: 50px;
    margin-top: -10px;
  }

  .leftTop {
    font-size: 14px;
  }

  .labelData {
    height: auto;
    width: auto;
  }

  .rightPhoto {
    position: absolute;
    text-align: center;
    right: 40px;
    top: 100px;
    font-size: 14px;
  }
  .leftB{
    width: 200px;
    position: relative;
  }
  .applyTime{
    position: relative;
    text-align: center;
    margin-left: 150px;
    top:-40px;
    color: #fe7f35;
    font-size: 12px;
  }
  .applyBt{
    position: relative;
    top: -80px;
    float: right;
    right: 30px;
    background-color: #fe7f35;
    border-radius: 0;
    border: none;
    box-shadow: 2px 2px 5px #fe7f35;
  }
  .blackImage{
    position: relative;
    top:-215px;
    z-index: 0;
  }
  .Baz{
    box-shadow: none;
  }
</style>
