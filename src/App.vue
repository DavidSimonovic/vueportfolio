<template>
  <div id="app">
  
  <Navbar/>
 
  <Welcome/>
  
  <Skills/>
  
  <Projects/>

  <About/>

 <Contact/>
 
 <Footer/>
  
  
</div>
</template>

<script>

import Welcome from './components/Welcome.vue'
import Skills from './components/Skills.vue'
import Navbar from './components/Navbar'
import Footer from './components/Footer.vue'

import Projects from './components/Projects.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Welcome,
    Skills,
    Projects,
    About,
    Footer

  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Monoton&display=swap');
</style> 
