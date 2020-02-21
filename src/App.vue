<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"/> -->
    <router-view/>
    <FooterGuide v-show="$route.meta.showFooter"></FooterGuide>
  </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide'

  export default {
    name: "App",
    components: {
      FooterGuide,
    }
  };
</script>

<style lang="stylus" rel="stylesheet/stylus">
  #app
    width 100%
    height 100%
    background-color: rgba(225, 241, 242, 0.78);
</style>
