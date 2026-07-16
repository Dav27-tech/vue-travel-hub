<script setup>
defineProps({
  destination: Object,
});
</script>

<template>
  <div class="col-md-4 d-flex">
    <img
      class="card-img-top"
      :src="destination.image"
      :alt="destination.name"
    />
    <div class="card-body d-flex flex-column">
      <h4>{{ destination.name }}</h4>
      <p>{{ destination.country }}</p>
      <h5 class="text-primary">USD ${{ destination.price }}</h5>
      <button class="btn btn-outline-primary mt-auto">View Package</button>
    </div>
  </div>
</template>
