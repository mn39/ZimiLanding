<template>
  <div id="app">
    <zimiHeader />
    <zimiMain />
    <stiky-app></stiky-app>
    <user-review />
    <ZigZag />
    <zimi-footer></zimi-footer>
  </div>
</template>

<script>
import zimiMain from '@/components/ZimiMain.vue'
import zimiHeader from '@/components/ZimiHeader.vue'
import UserReview from '@/components/UserReview.vue'
import ZigZag from '@/components/zigZag.vue'
import ZimiFooter from '@/components/zimiFooter.vue'
import StikyApp from '@/components/stikyApp.vue'

export default {
  name: 'App',
  components: {
    zimiMain,
    zimiHeader,
    UserReview,
    ZigZag,
    ZimiFooter,
    StikyApp,
  },
}
</script>

<style>
#app {
  font-family: Pretendard, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}

body {
  margin: 0;
}
</style>
