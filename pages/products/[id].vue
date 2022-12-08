<template>
  <div>
    <p>Product detail for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione aut quod
      voluptatem aliquid rerum? Placeat commodi adipisci fugit voluptatem
      aspernatur.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta({
  layout: "products",
});
</script>

<style scoped></style>
