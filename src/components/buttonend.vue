<template>
  <div class="page">
    <div>
      <ul>
        <li>
          <a href="#">微信小程序开发</a>
        </li>
        <li>
          <a href="#">小程序定制</a>
        </li>
        <li>
          <a href="#">小程序开发</a>
        </li>
        <li>
          <a href="#">分销系统</a>
        </li>
        <li>
          <a href="#">小程序定制开发</a>
        </li>
        <li>
          <a href="#">网站建设</a>
        </li>
      </ul>
    </div>
    <div>
      <span>湖南灵猴网络科技有限公司 统一社会信用代码：91430103MA4PPR023L</span>
    </div>
    <div>
      <span>版权所有 2018-2020◎All Rights Reserved. 湘ICP备18015777号</span>
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
  height: 150px;
  /* width: 1920px; */
  margin: 0 auto;
  text-align: center;
  background: #444545;
  /* padding-top: 20px; */
}
.page > div:nth-of-type(1) ul li {
  display: inline;
}
.page > div:nth-of-type(1) ul li a {
  text-decoration: none;
  display: inline-block;
  padding: 25px 10px;
  color: rgba(255, 255, 255, 1);
  font-size: 18px;
}
.page > div:nth-of-type(1) ul li a:hover {
  color: #278ed7;
}
.page > div:nth-of-type(2) {
  font-size: 18px;
  color: rgba(255, 255, 255, 1);
}
.page > div:nth-of-type(3) {
  font-size: 14px;
  color: rgba(255, 255, 255, 1);
  position: relative;
  bottom: -30px;
}
</style>
