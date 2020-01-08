<template>
  <div class="home">
    <div class="page-one page">
      <div class="one-left">
        <img src="../assets/img/logo2.png" alt="" class="logo2" />
        <p>
          Dinoll Union隶属于北京迪诺联动营销策划有限公司，是数据黑洞的探索者，也是智能效应的研究者。
        </p>
        <p class="text-p">
          数据，是整个“网络系”的一个黑洞，越用越庞大智能，是数据大潮（黑洞）上的一场蝴蝶效应，一发不可拾人，是数据黑洞中的渺小节点，也是智能效应的传播介质，难以剥离营销，越来越离不开数据与智能。
        </p>

        <h2>迪诺联动，是数据黑洞的探索者，也是智能效应的研究者</h2>
      </div>
      <div class="one-right">
        <img src="../assets/img/one.png" alt="" />
      </div>
    </div>
    <div class="page-two page">
      <div class="page-two-inner">
        <img src="../assets/img/team.png" alt="" class="team-img" />
        <div class="page-two-text">
          <h3>团队是一切的核心，强大的团队才能产出漂亮的东西</h3>
          <p>
            迪诺联动目前已在北京、上海两地部署机构中心，为更好的提供客户专属活动营销策略解决方案，团队已整合华北，华东，<br />华中，西南等区域的优势资源，业务服务范围辐射至全国，核心团队成员均拥有同行业多年的优秀服务经验
          </p>
        </div>
      </div>
    </div>

    <div class="page-three page">
      <img src="../assets/img/f.png" alt="" class="f" />
      <h2>
        智能改变生活，数据粘连生活
      </h2>
      <h2>
        迪诺联动，以整合见长，以互动出类，以时效出众
      </h2>
      <div class="info">
        <p>联合将营销连点成片，互动把策略重垂成线，联合互动，才能见得着精彩纷呈的营销效果。致力于为众多行业客户<br>提供全方位一站式营销服务，通过精准化、互动式、传统与创新型营销手段的有效结合，帮助众多企业获得市场洞<br>察力，实现持续增长，增加品牌价值，提升目标群体忠诚度！
</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {},
};
</script>
<style lang="stylus" scope>
@import '../assets/css/var.stylus';
  .home
    background url('../assets/img/guang.png') no-repeat center
    background-size cover
    .page-one
      width $g-width
      margin 0 auto
      display flex
      align-items center
      color $font-color
      .one-left
        width 532px
        font-size 16px
        .logo2
          margin-bottom 133px
        h2
          font-size 20px
          margin-top 90px
        p
         line-height:30px;
        .text-p
          margin-top 30px
      .one-right
        margin-left 10px
        img
          width 492px
          height 740px
    .page-two
      width:100%;
      display flex
      justify-content flex-end
      .page-two-inner
        width:1383px;
        .team-img
          width 353px
          height 201px
        .page-two-text
          width 100%
          height:196px;
          background #000000
          box-sizing border-box
          padding 53px 45px
          p
            font-size:16px;\
            margin-top 20px
            font-weight:400;
            color:rgba(207,207,207,1);
            line-height:30px;
    .page-three
      width $g-width
      margin 250px auto 0
      box-sizing border-box
      padding-bottom 76px
      .f
        width 926px
        display block
        margin 0 auto 111px
      h2
        line-height 40px
        font-size 20px
        margin-left 60px
      .info
        margin-top 36px
        line-height 30px
        font-size 16px
        margin-left 60px
</style>
