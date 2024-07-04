<template>
  <div>
    <Navbar />
    <HeroSection />
    <ProjectsSection/>
    <ContactSection />
    <AboutSection />
 


  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import Navbar from '../components/Navbar.vue';


export default {
  components: {
    HeroSection,
    ProjectsSection,
    ContactSection,
    AboutSection,
    Navbar
  
  }
}
</script>./Index.vue
