<template>
  <div class="min-h-screen bg-white">
    <!-- Navigation -->
    <Navigation />

    <!-- Hero Section -->
    <HeroSection />

    <!-- About Section -->
    <AboutSection />

    <!-- Skills Section -->
    <SkillsSection />

    <!-- Projects Section -->
    <ProjectsSection />

    <!-- Contact Section -->
    <ContactSection />

    <!-- Footer -->
    <FooterSection />
  </div>
</template>

<script>
import Navigation from './Navigation.vue'
import HeroSection from './HeroSection.vue'
import AboutSection from './AboutSection.vue'
import SkillsSection from './SkillsSection.vue'
import ProjectsSection from './ProjectsSection.vue'
import ContactSection from './ContactSection.vue'
import FooterSection from './FooterSection.vue'

export default {
  name: 'Home',
  components: {
    Navigation,
    HeroSection,
    AboutSection,
    SkillsSection,
    ProjectsSection,
    ContactSection,
    FooterSection
  }
}
</script>