<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <footer>
      <FooterTop/>
      <FooterMiddle/>
      <FooterBottom/>
    </footer>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import FooterTop from './components/footer/FooterTop.vue';
import FooterMiddle from './components/footer/FooterMiddle.vue';
import FooterBottom from './components/footer/FooterBottom.vue';

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
    FooterMiddle,
    FooterBottom,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
