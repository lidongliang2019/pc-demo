<template>
  <div class="container">
    <div class="Header">
      <h1 class="twoHandHouse">二手房</h1>
      <p class="twoTitle">为你而选</p>
      <el-button type="text" class="seeMore">浏览更多</el-button>
      <div class="imaginaryLine">
      </div>
    </div>
    <div class="photoAlbum">
      <div class="photo" v-for="item in items">
        <el-image :src="item.images">
          <div slot="placeholder" class="image-slot">
            加载中<span class="dot">...</span>
          </div>
        </el-image>
        <div class="textState">
          {{item.text}}
          <span class="price">{{item.price}} </span>
        </div>
        <div class="show-modal">
          <button onclick="push">push</button>
        </div>
      </div>
<!--      <span class="aa" v-show="seen">-->
<!--        2123123132123-->
<!--      </span>-->
<!--      <span v-show="true">-->
<!--        12123121231-->
<!--      </span>-->
<!--      <span v-bind:title="message" v-if="seen" id="app2"> 悬停几秒</span>-->
    </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                seen:true,
                message:'页面加载于'+ new Date().toDateString(),
                items: [
                    {
                        images: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg',
                        text: '合景峰会九期',
                        price: '30万',
                    },
                    {
                        images: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg',
                        text: '合景峰会九期',
                        price: '30万',
                    },
                    {
                        images: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg',
                        text: '合景峰会九期',
                        price: '30万',
                    },
                    {
                        images: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg',
                        text: '合景峰会九期',
                        price: '30万',
                    },
                    {
                        images: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg',
                        text: '合景峰会九期',
                        price: '30万',
                    },
                    {
                        images: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg',
                        text: '合景峰会九期',
                        price: '30万',
                    },

                ],

            }
        },
        methods: {
            visible:function(){
                this.seen = true;
            },
            invisible:function(){
                this.seen = false;
            },

        }
    }
</script>

<style scoped>
  .container {
    position: relative;
    top: -636px;
    margin: 0;
    width: 100%;
    height: auto;
    background-color: #ffffff;
  }

  .Header {
    width: 930px;
    height: 100px;
    margin:  auto;
    background-color: #ffffff;
  }

  .photoAlbum {
    width: 930px;
    height: 420px;
    margin: 20px auto;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    background-color: #ffffff;
  }

  .twoHandHouse {
    position: relative;
    line-height: 145px;
    color: #fe7f35;
  }

  .twoTitle {
    position: relative;
    top: -103px;
    left: 120px;
    color: #999999;
  }

  .imaginaryLine {
    position: relative;
    top: -198px;
    left: 524px;
    width: 200px;
    height: 30px;
    border-bottom: 1px dashed #fe7f35;
  }

  .seeMore {
    position: relative;
    top: -147px;
    left: 872px;
    color: #000000;
  }

  .photo {
    width: 300px;
    height: 200px;
    overflow: hidden;
    display: block;
  }
  .photo:hover{
    background-color: #fe7f35;
    transform: scale(1.2) translateY(-20px);
    z-index: 10;
    box-shadow: 0 0 30px rgba(254, 127, 53, 0.5);
  }
  .textState {
    position: relative;
    top: -35px;
    padding-left: 20px;
    padding-top: 3px;
    width: 100%;
    height: 30px;
    color: white;
    background-color: #444c4c;
    opacity: 0.5;
  }

  .price {
    position: relative;
    left: 130px;
  }
</style>
