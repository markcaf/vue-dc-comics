<template>
  <div id="app">
    <Header/>
    <Jumbo/>
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
import Jumbo from './components/Jumbo.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
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
