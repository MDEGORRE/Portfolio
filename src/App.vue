<script setup>
import { onMounted } from 'vue'
import { initDropdowns } from 'flowbite';

import Navbar from './components/Navbar.vue';
import Timeline from './components/Timeline.vue';
import ContactForm from './components/ContactForm.vue';
import Jumbotron from './components/Jumbotron.vue';
import Competencies from './components/Competencies.vue';
import Projects from './components/Projects.vue';
import Footer from './components/Footer.vue';

onMounted(() => {
  initDropdowns();
})

</script>

<template>
  <Navbar />
  <Jumbotron />
  <Timeline />
  <Competencies />
  <Projects />
  <ContactForm />
  <Footer />
</template>
