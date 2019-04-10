<template>
  <div class="page" id="product">
    <div>
      <img src="../images/product.png" class="img_100">
    </div>
    <div class="ui-cell ui-cell-sa">定制</div>
    <div class="ui-cell ui-cell-sb main">
      <div class="ui-cell ui-cell-cl">
        <div class="img_101">
          <img src="../images/icon_1.png" alt srcset class="img_100">
        </div>
        <div class="main_body">
          <div>微信小程序开发</div>
          <div></div>
          <div>微信10亿流量入口， 先做先抢流量红利</div>
        </div>
      </div>
      <div class="ui-cell ui-cell-cl">
        <div class="img_102">
          <img src="../images/icon_2.png" alt srcset class="img_100">
        </div>
        <div class="main_body">
          <div>APP开发</div>
          <div></div>
          <div>
            营销功能强大的平
            台，让消费者更便
            捷的使用
          </div>
        </div>
      </div>
      <div class="ui-cell ui-cell-cl">
        <div class="img_103">
          <img src="../images/icon_3.png" alt srcset class="img_100">
        </div>
        <div class="main_body">
          <div>微信公众号开发</div>
          <div></div>
          <div>
            给个人、企业提供业
            务服务与用户管理能
            力的全新服务平台
          </div>
        </div>
      </div>
      <div class="ui-cell ui-cell-cl">
        <div class="img_104">
          <img src="../images/icon_4.png" alt srcset class="img_100">
        </div>
        <div class="main_body">
          <div>企业VI形象设计</div>
          <div></div>
          <div>
            帮助企业建立文化IP，
            扩大企业宣传影响力
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  data() {
    return {};
  },
  components: {}
};
</script>

<style scoped>
.page {
  height: 676px;
  /* width: 1920px; */
  background: #f3f3f3;
}
.page > div:nth-of-type(1) {
  height: 90px;
  width: 220px;
  background: #f3f3f3;
  padding-top: 50px;
  margin: 0 auto;
}
.page > div:nth-of-type(2) {
  font-size: 60px;
  font-weight: bold;
  color: rgba(0, 0, 0, 1);
  padding-top: 58px;
}
.main {
  margin: 0px 260px;
}
.main_body div:nth-of-type(1) {
  width: 294px;
  height: 42px;
  font-size: 42px;
}
.main_body div:nth-of-type(2) {
  width: 61px;
  height: 10px;
  background: #0671bc;
  margin-top: 20px;
}
.main_body div:nth-of-type(3) {
  width: 292px;
  height: 81px;
  font-size: 32px;
  font-family: MicrosoftYaHeiLight;
  font-weight: 300;
  color: rgba(102, 102, 102, 1);
  line-height: 50px;
}
/*
.page > div:nth-of-type(3) {
  padding: 0px 348px;
  margin-top: 51px;
  font-size: 42px;
  font-weight: 400;
  color: rgba(0, 0, 0, 1);
}
.page > div:nth-of-type(4) {
  padding:0px 273px 0px 260px;
}
.page > div:nth-of-type(4) div span:nth-of-type(1) {
  font-size: 42px;
  font-weight: 400;
  color: rgba(0, 0, 0, 1);
}
.page > div:nth-of-type(4) div span:nth-of-type(2) {
  height: 10px;
  width: 61px;
  background: #0671bc;
  display: block;
  margin-top: 5px;
}
.page > div:nth-of-type(4) div span:nth-of-type(3) {
  font-size: 32px;
  font-weight: 300;
  color: rgba(102, 102, 102, 1);
  display: block;
  width: 300px;
  height: 204px;
  margin-top: 20px;
}
.page > div:nth-of-type(4) div:nth-of-type(2){
  margin-left: 10px
}
.page > div:nth-of-type(4) div:nth-of-type(3){
  margin-left: 10px
}.page > div:nth-of-type(4) div:nth-of-type(4 ){
  margin-left: 10px
}
.hx::after {
  content: "";
  height: 10px;
  width: 61px;
  position: absolute;
  bottom: -10px;
  background: #0671bc;
  left: 0px;
}
*/
.img_101 {
  height: 119px;
  width: 118px;
}
.img_102 {
  height: 110px;
  width: 110px;
}
.img_103 {
  height: 110px;
  width: 134px;
}
.img_104 {
  height: 110px;
  width: 97px;
}
</style>
