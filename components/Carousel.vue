<template>
  <UCarousel
    ref="carouselRef"
    v-slot="{ item }"
    :items="items"
    class="rounded-lg overflow-hidden ui-size"
    indicators
    arrows
  >
    <img :src="item" class="w-full" draggable="false" />
  </UCarousel>
</template>

<script setup lang="ts">
const items = [
  "https://picsum.photos/1920/1080?random=1",
  "https://picsum.photos/1920/1080?random=2",
  "https://picsum.photos/1920/1080?random=3",
  "https://picsum.photos/1920/1080?random=4",
  "https://picsum.photos/1920/1080?random=5",
  "https://picsum.photos/1920/1080?random=6",
];

const carouselRef = ref();

onMounted(() => {
  setInterval(() => {
    if (!carouselRef.value) return;

    if (carouselRef.value.page === carouselRef.value.pages) {
      return carouselRef.value.select(0);
    }

    carouselRef.value.next();
  }, 7000);
});
</script>

<style scoped>
.ui-size {
  height: 400px;
}
.ui-size img {
  width: fit-content;
}
/* 400x1600 mais ou menos a dimensão da imagem para testar */
</style>
