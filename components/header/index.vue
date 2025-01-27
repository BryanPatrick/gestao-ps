<script setup>
const items = reactive([
  {
    label: "Inicio",
    to: "/",
    description: "Voltar ao inicio",
  },
  {
    label: "Chamados",
    to: "/Chamados",
    description: "Ir para área de chamados",
  },
  {
    label: "Treinamentos",
    to: "/treinamentos",
    description: "Ir a pagina treinamentos",
  },
  {
    label: "Gerenciamento",
    to: "/gerenciamento",
    description: "Ir a pagina gerenciamento",
  },
]);
</script>

<template>
  <header class="flex h-16 justify-between">
    <div class="flex items-center py-2 w-80 justify-center">
      <img
        class="h-full px-2"
        src="../../assets/icon-alpha.png"
        alt="Instituto Alpha"
      />
      <h3 class="text-xl font-semibold">
        <span class="text-teal-900 font-bold">Alpha </span>
        <span class="text-gray-500">Instituto Cubatão</span>
      </h3>
    </div>
    <div class="flex">
      <nuxtLink
        class="flex items-center mx-8 text-lg font-semibold text-teal-900"
        :to="item.to"
        v-for="item in items"
        :key="item.label"
      >
        {{ item.label }}
      </nuxtLink>
    </div>
    <div class="w-80"></div>
  </header>
</template>
