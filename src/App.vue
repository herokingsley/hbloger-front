<template>
  <div class="container-fluid">
    <div id="app" class="row">
      <!--<img src="./assets/logo.png">-->
      <left-nav></left-nav>
      <banner></banner>
      <content></content>
      <footer></footer>
    </div>
  </div>
</template>

<script>
import Banner from './components/Banner'
import Content from './components/Content'
import Footer from './components/Footer'
import LeftNav from './components/LeftNav'

export default {
  name: 'app',
  components: {
    LeftNav,
    Banner,
    Content,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
