<script setup>
const newsCard = reactive([
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
  {
    title: "Titulo",
    date: "Data",
    description: `
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti saepe
      ad, iste debitis optio deserunt consequuntur a eum aspernatur architecto
      dicta beatae itaque consequatur ducimus, praesentium facere culpa quis
      quam?`,
    to: "",
    priority: 1,
  },
]);
</script>

<template>
  <div class="h-48 w-full mx-4 my-4 overflow-hidden relative">
    <div class="h-40 w-full z-10 absolute bottom-4 left-10 top-4 rounded-xl">
      <img
        class="h-full rounded-xl"
        src="../../assets/outubro-rosa.jpg"
        alt="imagem da campanha outubro rosa"
      />
    </div>
    <div
      style="border: 2px solid gray"
      class="w-[90%] h-full float-right rounded-xl"
    >
      <div class="float-right w-[82%] h-full p-3 rounded-xl relative">
        <h3>Novembro rosa</h3>
        <p class="my-3 text-wrap">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quo autem
          assumenda dolore nam totam voluptates possimus, facilis atque
          molestias veritatis quos labore nulla velit ullam! Magni unde
          dignissimos voluptatibus autem?
        </p>
        <UButton color="blue" variant="solid" class="absolute bottom-3"
          >Ver mais !</UButton
        >
      </div>
    </div>
  </div>
  <div class="h-48 w-full mx-4 my-4 overflow-hidden relative">
    <div class="h-40 w-full z-10 absolute bottom-4 left-10 top-4 rounded-xl">
      <img
        class="h-full w-[246px] rounded-xl"
        src="../../assets/novembro-azul.jpg"
        alt="imagem da campanha novembro azul"
      />
    </div>
    <div
      style="border: 2px solid gray"
      class="w-[90%] h-full float-right rounded-xl"
    >
      <div class="float-right w-[82%] h-full p-3 rounded-xl relative">
        <h3>Outubro azul</h3>
        <p class="my-3 text-wrap">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quo autem
          assumenda dolore nam totam voluptates possimus, facilis atque
          molestias veritatis quos labore nulla velit ullam! Magni unde
          dignissimos voluptatibus autem?
        </p>
        <UButton color="blue" variant="solid" class="absolute bottom-3"
          >Ver mais !</UButton
        >
      </div>
    </div>
  </div>
</template>
