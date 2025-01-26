<script>
import MidleLinks from "./MidleLinks.vue";
</script>

<template>
  <div class="px-20">
    <div class="flex">
      <div class="news flex flex-row justify-center flex-wrap">
        <BottomAreaMidleLinks />
        <BottomAreaNewsCard />
      </div>
      <div class="links flex justify-center">
        <BottomAreaAsideLinks />
      </div>
    </div>
  </div>
</template>

<style>
.news {
  width: 80%;
}
.links {
  width: 20%;
  height: fit-content;
}
</style>
