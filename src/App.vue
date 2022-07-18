<template>
  <div id="app">
    <Header/>
    <Main/>
    <MarketDC/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import MarketDC from './components/MarketDC.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    MarketDC,
    Footer,
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";
@import "./styles/variables.scss";

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
</style>
