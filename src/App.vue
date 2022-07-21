<template>
  <div id="app">
    <div>
      <MyTitle />
      <MyHero />
    </div>
  </div>
</template>

<script>
import MyTitle from "./components/Title.vue";
import MyHero from "./components/Hero.vue";

export default {
  name: 'App',
  components: {
  MyTitle,
  MyHero
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ff0000;
  margin-top: 60px;
}
</style>
