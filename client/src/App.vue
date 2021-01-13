<template>
  <div id="app">
    <MainScreen msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import MainScreen from './components/MainScreen.vue'

export default {
  name: 'App',
  components: {
    MainScreen
  }
}
</script>

<style>
@import './assets/css/skeleton/css/normalize.css'
@import './assets/css/skeleton/css/skeleton.css';
</style>
