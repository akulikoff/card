<script setup lang="ts">
import Card from "./components/Card.vue";
const data = {
  title: "Top 5 Living Room Inspirations",
  teaserText: "Interior",
  description:
    "Curated vibrants colors for your living, make it pop & calm in the same time.",
  imageUrl: "/spacejoy-YqFz7UMm8qE-unsplash.jpg",
  link: "#",
};
</script>

<template>
  <Card v-bind="data" />
</template>

<style scoped></style>
