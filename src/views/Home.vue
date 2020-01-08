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
    width $g-width
    margin 0 auto
    .page-one
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
</style>
