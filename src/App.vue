<template>
  <div id="app">
    <my-header />
    <router-view/>
  </div>
</template>
<script>
import MyHeader from '@/components/base/MyHeader.vue';

export default {
  components: {
    MyHeader,
  },
};
</script>
<style lang="stylus">
@import './assets/css/base.stylus';
</style>
