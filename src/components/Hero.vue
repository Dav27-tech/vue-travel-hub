<script setup>
function explorePackage() {
  alert("let's explore the world!");
}
</script>

<template>
  <section class="hero bg-light py-5">
    <div class="container text-center">
      <h1 class="display-3 fw-bold">Discover Your Next Adventure</h1>
      <p class="lead my-4">
        Explore beautiful destinations around the world with exclusive travel
        packages.
      </p>
      <button class="btn btn-primary btn-lg" @click="explorePackage">
        Explore Package
      </button>
    </div>
  </section>
</template>
