<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Destinations from "./components/Destinations.vue";
import Footer from "./components/Footer.vue";
import destinations from "./data/destination.js";
</script>

<template>
  <Navbar />
  <main>
    <Hero />
    <destinations />
  </main>
  <Footer />
</template>
