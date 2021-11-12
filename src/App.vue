<template>
  <div id="app">
    <Header></Header>
    <Hero></Hero>
    <Main></Main>
    <BlueSection></BlueSection>
    <Footer></Footer>
    <Social></Social>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Main from './components/Main.vue'
import BlueSection from './components/BlueSection.vue'
import Footer from './components/Footer.vue'
import Social from './components/Social.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Main,
    BlueSection,
    Footer,
    Social
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
