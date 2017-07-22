<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
  import Vue from 'vue'
  import VueResource from 'vue-resource'
  Vue.use(VueResource);

  import { flexibleCss } from './js/lib/properScreen_css'
  import { flexible } from './js/lib/properScreen'
  flexibleCss();
  flexible();

  import './less/common.less'

  export default {
    name: 'app'
  }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
