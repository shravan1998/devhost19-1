<template>
  <div>
   <Header />
   <Ldpage />
   <About />
   <Speakers />
   <Schedule />
   <Sponsors />
   <Footer />
  </div>
</template>

<script>
import Header from './components/header.vue'
import Ldpage from './components/landingpage.vue'
import About from './components/about.vue'
import Speakers from './components/speakers.vue'
import Schedule from './components/schedule.vue'
import Sponsors from './components/sponsor.vue'
import Footer from './components/footer.vue'

export default {
  name: 'app',
  components: {
    Header,
    Ldpage,
    About,
    Speakers,
    Schedule,
    Sponsors,
    Footer
  }
}
</script>

<style>
body{
  overflow: auto;
  margin:auto;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
