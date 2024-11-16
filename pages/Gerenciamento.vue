<script setup>
const items = reactive([
  {
    label: "Dashboard",
    Users: "teste",
  },
]);
</script>

<template>
  <div>
    <Header />
    <ul>
      <li v-for="item in items">
        {{ item }}
      </li>
    </ul>
  </div>
</template>
