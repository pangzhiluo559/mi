<template>
  <div class="bg-white">
    <div class="w-2/3 mx-auto">
      <topNav/>
    </div>
  </div>
  <div class="w-full bg-slate-50">
    <div class="w-2/3 mx-auto ">
      <homeIndex />
      <picIndex />
    </div>
  </div>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  
  <div class="w-full bg-white">
    <indexFooter/>
  </div>
</template>

<script>
import topNav from './components/topNav.vue'
import homeIndex from './components/homeIndex.vue'
import picIndex from './components/picIndex.vue'
import indexFooter from './components/indexFooter.vue'

export default {
  name: 'App',
  components: {
    topNav,
    homeIndex,
    picIndex,
    indexFooter
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
  /* margin-top: 60px; */
}
</style>
