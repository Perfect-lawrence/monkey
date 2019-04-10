<template>
  <div class="page" id="about">
    <div>
      <img src="../images/about.png" class="img_100">
    </div>
    <div class="page_main">
      <div>
        <div>湖南灵猴网络科技有限公司</div>
        <div>“灵猴“就是灵动活跃，丰富的互联网经验，独特的设计风格，灵猴用匠心为您精挑细选，给您私人订制般的完美设计体验。思想是设计的灵魂，文化是设计的最高表现。我们不仅仅满足是客户的功能需求，还有满足客户的个性需求和个性差异，为您打造专属于您的设计。</div>
      </div>
      <div>
        <img src="../images/about-right.png" class="img_100">
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
  /* width: 1392px; */
  height: 1130px;
  background: white;
  margin: 0 264px;
}
.page > div:nth-of-type(1) {
  height: 90px;
  width: 220px;
  padding-top: 50px;
  margin: 0 auto;
}
.page_main{
  padding-top: 50px;

}
.page_main>div:nth-of-type(1){
    float: left;
    text-align: left
}
.page_main>div:nth-of-type(1)>div:nth-of-type(1){
font-size:55px;
font-weight:bold;
}
.page_main>div:nth-of-type(1)>div:nth-of-type(2){
width:624px;
font-size:48px;
font-weight:400;
color:rgba(102,102,102,1);
line-height:70px;
margin-top: 50px
}
.page_main>div:nth-of-type(2){
    width: 708px;
    height: 818px;
    float:right;
    position:relative;
    top: -40px
}
</style>

