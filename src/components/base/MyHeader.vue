<template>
  <nav class="nav-warp">
    <div class="nav-inner">
      <div class="logo">
        <img src="../../assets/img/logo.png" alt="" />
      </div>
      <ul class="nav-bar">
        <router-link tag="li" to="/">公司简介</router-link>
        <router-link tag="li" to="/concept">服务理念</router-link>
        <router-link tag="li" to="/service">迪诺服务</router-link>
        <router-link tag="li" to="/case">案例中心</router-link>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'MyHeader',
};
</script>

<style lang="stylus" scoped>
@import '../../assets/css/var.stylus';
$headr-height = 120px
$header-width = 212px
$bordercolor = linear-gradient(to right,#0b161e,#162e41, #2d5c82,#2d5c82,#162e41,#0b161e)
.nav-warp
    width 100%
    height $headr-height
    background-color $header-bg
.nav-inner
    width $g-width
    height $headr-height
    margin 0 auto
    display flex
    justify-content space-between
    align-items center
    .logo
        width 185px
        height 64px
        img
            width 90%
    .nav-bar
        width $residue(1200, 185+136)
        display flex
        justify-content space-between
        li
            width $header-width
            height $residue($headr-height, 4)
            line-height $residue($headr-height, 4)
            text-align center
            color $font-color
            cursor pointer
        .router-link-active
            border-bottom 4px solid
            border-image $bordercolor 4
</style>
