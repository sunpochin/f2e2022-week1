<template>
  <HelloWorld msg="F2E week 1 project placeholder"/>
  <HomeViewVue />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HomeViewVue from './views/HomeView.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    HomeViewVue,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
