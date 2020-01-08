<template>
  <footer class="footer">
    <div class="footer-inner">
      <div class="left">
        <p>
          联系我们
        </p>
        <p>北京总部：北京是通州区新华北路117号通惠1933创意园325室</p>
        <p>上海总部：上海市徐汇区石龙路345弄德必 易园23号A座</p>
        <p>联系电话：400-680-9588</p>
      </div>
      <div class="right">
        <p>官方微信</p>
        <img src="../../assets/img/qrcode.png" alt="" />
      </div>
    </div>
    <p class="copyright">京ICP备17027485号-1</p>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
@import '../../assets/css/var.stylus';
$bordercolor = linear-gradient(to right,#0b161e,#162e41, #2d5c82,#2d5c82,#162e41,#0b161e)
.footer
  background #000000
  height 450px
  width 100%
  color #666666
  line-height:40px;
  font-size:16px;
  .footer-inner
    width $g-width
    margin 0 auto
    box-sizing border-box
    padding 0 226px
    display flex
    align-items center
    height 90%
    .item
      height 100%
    .right
      width 143px
      text-align center
      margin-bottom 22px
      margin-left 100px
      img
        width 100%
  .copyright
    width 100%
    text-align center
</style>
