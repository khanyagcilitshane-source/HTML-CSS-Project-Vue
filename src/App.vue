<script setup>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Interests from './components/Interests.vue'
import Contact from './components/Contact.vue'
</script>

<template>
  <Navbar />

  <main>
    <Home />
    <About />
    <Skills />
    <Projects />
    <Interests />
    <Contact />
  </main>

  <footer>
    <p>&copy; 2026 Khanya Gcilitshane. All Rights Reserved.</p>
  </footer>
</template>