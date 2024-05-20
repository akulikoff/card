<script setup lang="ts">
import { ref } from "vue";

// defineProps<{ title: string }>();
</script>

<template>
  <body class="bg-gradient-to-b from-grey-50 to-grey-300">
    <div class="card flex flex-col justify-center px-4 mx-auto">
      <img
        src="/spacejoy-YqFz7UMm8qE-unsplash.jpg"
        alt="teaser"
        loading="lazy"
        class="rounded-t-lg object-cover w-full h-72"
      />
      <article class="bg-white rounded-b-lg p-4 shadow-md">
        <div class="my-4">
          <span
            class="bg-green-50 rounded-full px-2 py-0.5 border border-green-200 text-green-700 text-sm font-medium"
            >Interior</span
          >
        </div>
        <h3 class="text-lg text-neutral-900 font-semibold mb-2 line-clamp-1">
          Top 5 Living Room Inspirations
        </h3>
        <p class="text-neutral-600 mb-2 font-medium text-base line-clamp-2">
          Curated vibrants colors for your living, make it pop & calm in the
          same time.
        </p>

        <a
          href="#"
          class="text-indigo-700 text-base font-medium my-1 p-0.5 inline-block focus:outline focus:outline-4 rounded-sm focus:outline-indigo-200 focus:p-0.5 disabled:text-neutral-600 disabled:cursor-not-allowed"
          >Read more <span class="ml-1">&#129122;</span></a
        >
      </article>
    </div>
  </body>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
