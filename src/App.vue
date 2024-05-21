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

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
./components/Card.vue
