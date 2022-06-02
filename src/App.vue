<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <FooterTop/>
    <FooterMiddle/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import FooterTop from './components/footer/FooterTop.vue';
import FooterMiddle from './components/footer/FooterMiddle.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
    FooterMiddle,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
