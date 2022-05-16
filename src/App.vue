<template>
  <div id="app">
    <MyTitle />
    <MyHero />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyTitle from "./components/MyTitle.vue";
import MyHero from "./components/MyHero.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MyTitle,
    MyHero,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
