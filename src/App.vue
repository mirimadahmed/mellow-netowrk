<template>
  <div id="app" class="w-100 h-100">
    <Intro />
    <div class="container">
      <div class="col-12">
        <p>Some of our brands...</p>
      </div>
      <Brands />
      <Jobs />
    </div>
  </div>
</template>

<script>
import Intro from './components/Intro.vue'
import Brands from './components/Brands.vue'
import Jobs from './components/Jobs.vue'

export default {
  name: 'App',
  components: {
    Intro,
    Brands,
    Jobs
  }
}
</script>

<style>
#app {
  font-family: "Potta One", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #ffdb49;
}
</style>
