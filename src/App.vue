<template>
  <div id="app" class="container-fluid">
   <the-header/>
    <the-left-view/>
 
    <the-right-view/>
 
  <!-- <div class="">This div takes up 1/3 of the available width on a desktop</div>
  <div class="">This div takes up 2/3 of the available width on a desktop</div> -->
   </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheLeftView from './components/TheLeftView.vue'
import TheRightView from './components/TheRightView.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    TheLeftView,
    TheRightView
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
