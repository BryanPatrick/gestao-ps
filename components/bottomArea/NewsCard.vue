<script setup>
const newsCard = reactive([
  {
    title: "Um texto qualquer para exemplificar",
    image: "bg-[url('')]",
    description: `
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
          quidem doloribus nesciunt voluptatibus! Voluptatum repellat, sapiente
          id nulla deserunt ipsa aliquid eum ad nam praesentium corporis,
          nostrum nemo dolore harum?`,
    button: "Saber mais",
    to: "logo ali",
    local: "PSC",
  },
  {
    title: "Um texto qualquer para exemplificar",
    description: `
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
          quidem doloribus nesciunt voluptatibus! Voluptatum repellat, sapiente
          id nulla deserunt ipsa aliquid eum ad nam praesentium corporis,
          nostrum nemo dolore harum?`,
    button: "Saber mais",
    to: "logo ali",
    local: "PSI",
  },
  {
    title: "Um texto qualquer para exemplificar",
    description: `
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
          quidem doloribus nesciunt voluptatibus! Voluptatum repellat, sapiente
          id nulla deserunt ipsa aliquid eum ad nam praesentium corporis,
          nostrum nemo dolore harum?`,
    button: "Saber mais",
    to: "logo ali",
    local: "PSI",
  },
]);
</script>

<template>
  <div class="w-full my-5 text-center">
    <h2 class="text-xl font-semibold">Últimas noticias</h2>
    <p class="font-light text-xs">Para mais noticias clicar em saber mais</p>
  </div>
  <div class="py-5 mx-10" v-for="item in newsCard">
    <article class="w-60 h-[506px] shadow-xl overflow-hidden">
      <div class="h-[40%] relative" style="background-color: green">
        <span
          class="absolute right-0 top-0 bg-white w-10 text-center rounded-xl"
          >{{ item.local }}</span
        >
        <img
          class="h-full bg-auto"
          src="./../../assets/novembro-azul.jpg"
          alt="Imagem"
        />
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
