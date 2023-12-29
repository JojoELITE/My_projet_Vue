<template>

  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Presentation/>
  <Partenary/>
  <About/>
  <Services/>
  <Web/>
  <Milestones/>
  <Projects/>
  <Testimonials/>
  <Contact/>
  <Footer/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Presentation from './components/Presentation.vue'
import Partenary from './components/Partenary.vue'
import About from './components/About.vue'
import Services from './components/Services.vue'
import Web from './components/Web.vue'
import Milestones from './components/Milestones.vue'
import Projects from './components/Projects.vue'
import Testimonials from './components/Testimonials.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, Presentation,Partenary, About, Services, Web, Milestones, Projects, Testimonials, Contact, Footer
  }
}
</script>

<style>

</style>
