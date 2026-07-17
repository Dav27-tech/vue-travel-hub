<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Destinations from "./components/Destinations.vue";
import Footer from "./components/Footer.vue";
import destinations from "./data/destinations.js";
import Benefits from "./components/Benefits.vue";
</script>

<template>
  <Navbar />
  <main>
    <Hero />
    <Destinations />
    <Benefits />
  </main>
  <Footer />
</template>
