<template>
  <div id="app">
    <Head></Head>
    <AboutMe></AboutMe>
    <Social></Social>
    <Footer></Footer>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Head from './components/Head';
import AboutMe from './components/AboutMe';
import Social from './components/Social';
import Footer from './components/Footer';

export default {
  name: 'app',
  components: {
    HelloWorld,
    Head,
    AboutMe,
    Social,
    Footer,
  },
};
</script>

<style>
#app {
  padding: 0, 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

</style>
