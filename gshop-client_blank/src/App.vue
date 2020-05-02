<template>
  <div>
    <!-- 引入组件 -->
    <router-view/>
    <FooterGuide/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import FooterGuide from './components/FooterGuide/FooterGuide.vue'


export default {
  // name: 'App',
  components: {
    FooterGuide
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .app
    color read
  
</style>
