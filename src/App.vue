<template>
  <div id="app">
    <navbar-app/>
    <jumbotron-app/>  
    <main-app/>  
    <footer-app/>
  </div>
</template>

<script>
import NavbarApp from './components/NavbarApp.vue'
import JumbotronApp from './components/JumbotronApp.vue'
import MainApp from './components/MainApp.vue'
import FooterApp from './components/FooterApp.vue'
export default {
  name: 'App',
  components: {
    NavbarApp,
    JumbotronApp,
    MainApp,
    FooterApp
  }
}
</script>

<style lang="scss">
  @import './style/main.scss'
</style>
