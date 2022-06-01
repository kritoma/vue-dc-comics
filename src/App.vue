<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <FooterTop/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import FooterTop from './components/footer/FooterTop.vue';

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
