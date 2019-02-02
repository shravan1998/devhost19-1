<template>
  <div>
   <Header />
   <Ldpage />
   <About />
   <Speakers />
  </div>
</template>

<script>
import Header from './components/header.vue'
import Ldpage from './components/landingpage.vue'
import About from './components/about.vue'
import Speakers from './components/speakers.vue'


export default {
  name: 'app',
  components: {
    Header,
    Ldpage,
    About,
    Speakers,
    
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
