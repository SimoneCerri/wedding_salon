<template>
  <!-- The App component simply orchestrates the single-page flow by listing the sections -->
  <main>
    <HeroSection />
    <ServicesSection />
    <GallerySection />
    <TestimonialsSection />
    <ContactSection />
    <Footer />
  </main>
</template>

<script setup>
import HeroSection from './components/HeroSection.vue';
import ServicesSection from './components/ServicesSection.vue';
import GallerySection from './components/GallerySection.vue';
import TestimonialsSection from './components/TestimonialsSection.vue';
import ContactSection from './components/ContactSection.vue';
import Footer from './components/Footer.vue';

// No global state or logic needed in App.vue, it just composes the page.
</script>

<style>
/* Global styles for App.vue or shared layout elements */
body {
  padding-top: 0;
  /* No fixed navbar needed for a simple landing page */
}
</style>
