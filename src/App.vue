<template>
  <NavBar />
  <HomeViewVue />
</template>

<script>
import NavBar from './components/NavBar.vue'
import HomeViewVue from './views/HomeView.vue';
export default {
  name: 'App',
  components: {
    NavBar,
    HomeViewVue,
  }
}
</script>

<style>
body {
  margin: 0px;
  padding: 0px;
  background-color: #06102B;
}

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50; */
  /* margin-top: 60px; */
}
</style>
