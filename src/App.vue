<template>
  <div id="app">
    <zimiHeader />
    <zimiMain />
  </div>
</template>

<script>
import zimiMain from "./components/ZimiMain.vue";
import zimiHeader from "./components/ZimiHeader.vue";
export default {
  name: "App",
  components: {
    zimiMain,
    zimiHeader,
  },
};
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
</style>
