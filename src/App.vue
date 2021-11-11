<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <BlueSection></BlueSection>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import BlueSection from './components/BlueSection.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    BlueSection,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
@import 'styles/variables';
@import 'styles/main';
</style>
