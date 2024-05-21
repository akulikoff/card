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
  <Card
    :title="data.title"
    :teaserText="data.teaserText"
    :description="data.description"
    :imageUrl="data.imageUrl"
    :link="data.link"
  />
</template>

<style scoped></style>
