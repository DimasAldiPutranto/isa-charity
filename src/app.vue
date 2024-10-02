<template>
  <div id="app">
    <Header />
    <HeroSection />
    <AboutSection />
    <ProjectsSection />
    <QuoteSection />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import HeroSection from './components/HeroSection.vue';
import AboutSection from './components/AboutSection.vue';
import ProjectsSection from './components/ProjectsSection.vue';
import QuoteSection from './components/QuoteSection.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Header,
    HeroSection,
    AboutSection,
    ProjectsSection,
    QuoteSection,
    Footer
  }
};
</script>
