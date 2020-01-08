<template>
  <div id="app">
    <my-header />
    <router-view/>
    <my-footer />
  </div>
</template>
<script>
import MyHeader from '@/components/base/MyHeader.vue';
import MyFooter from '@/components/base/MyFooter.vue';

export default {
  components: {
    MyHeader,
    MyFooter,
  },
};
</script>
<style lang="stylus">
@import './assets/css/base.stylus';
</style>
