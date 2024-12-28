<script setup>
const newsCard = reactive([
  {
    title: "Um texto qualquer para exemplificar",
    image: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
          quidem doloribus nesciunt voluptatibus! Voluptatum repellat, sapiente
          id nulla deserunt ipsa aliquid eum ad nam praesentium corporis,
          nostrum nemo dolore harum?`,
    button: "Saber mais",
    to: "logo ali",
  },
  {
    title: "Um texto qualquer para exemplificar",
    image: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
          quidem doloribus nesciunt voluptatibus! Voluptatum repellat, sapiente
          id nulla deserunt ipsa aliquid eum ad nam praesentium corporis,
          nostrum nemo dolore harum?`,
    button: "Saber mais",
    to: "logo ali",
  },
  {
    title: "Um texto qualquer para exemplificar",
    image: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
          quidem doloribus nesciunt voluptatibus! Voluptatum repellat, sapiente
          id nulla deserunt ipsa aliquid eum ad nam praesentium corporis,
          nostrum nemo dolore harum?`,
    button: "Saber mais",
    to: "logo ali",
  },
]);
</script>

<template>
  <div class="py-5 ml-16" v-for="item in newsCard">
    <article class="w-60 h-96 shadow-xl overflow-hidden">
      <div class="h-[40%]" style="background-color: green">
        <img :src="item.image" alt="Imagem" />
      </div>
      <div class="h-[45%] p-2">
        <h3 class="text-center text-xl font-bold">
          {{ item.title }}
        </h3>
        <p class="text-xs font-light pt-2 text-center">
          {{ item.description }}
        </p>
      </div>
      <div class="h-[15%] flex items-center justify-center">
        <button class="w-24 h-10 rounded-md" style="background-color: green">
          {{ item.button }}
        </button>
      </div>
    </article>
  </div>
</template>
