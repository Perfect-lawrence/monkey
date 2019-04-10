<template>
  <div class="page ui-cell ui-cell-sb" id="dingbu">
    <div>
      <img src="../images/title.png" alt srcset class="img_100">
    </div>
    <div>
      <ul class="ui-cell">
        <li>
          <a href="#">首页</a>
        </li>
        <li>
          <a href="#product">产品中心</a>
        </li>
        <li>
          <a href="#CaseShow">案列展示</a>
        </li>
        <li>
          <a href="#about">关于我们</a>
        </li>
        <li>
          <a href="https://shop274783214.taobao.com/" target="_black">淘宝店铺</a>
        </li>
      </ul>
    </div>
    <div>咨询电话
      <br>0731-85516676
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
  /* width: 1406px; */
  height: 94px;
  background: #ffffff;
  padding: 0px 257px;
}
.page div:first-of-type {
  height: 55px;
  width: 133px;
}
.page div:nth-of-type(2) {
  font-size: 22px;
  font-family: MicrosoftYaHei;
  font-weight: 400;
}
.page div:nth-of-type(2) li a {
  display: block;
  padding-bottom: 11px;
  text-decoration: none;
  border-bottom: 5px solid transparent;
}
.page div:nth-of-type(2) li {
  display: block;
  margin-left: 64px;
}
.page div:nth-of-type(2) li:first-of-type a {
  border-bottom: 5px solid #0670bb;
}
.page div:nth-of-type(2) li:first-of-type:hover {
  border-bottom: transparent;
}
.page div:nth-of-type(2) li a:hover {
  text-decoration: none;
  color: #0670bb;
  border-bottom: 5px solid #0670bb;
}
.page div:nth-of-type(2) li:first-of-type a {
  font-size: 22px;
  font-weight: bold;
  color: rgba(6, 112, 187, 1) !important;
}
.page div:nth-of-type(3) {
  font-size: 22px;
  font-weight: bold;
}
</style>
