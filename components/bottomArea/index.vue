<script>
import MidleLinks from "./MidleLinks.vue";
</script>

<template>
  <div class="px-5">
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
  width: 84%;
}
.links {
  width: 16%;
  height: fit-content;
}
</style>
