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
    label: "Setores",
    to: "/setores",
    description: "Ir a pagina setores",
  },
  {
    label: "Gerenciamento",
    to: "/gerenciamento",
    description: "Ir a pagina gerenciamento",
  },
]);
</script>

<template>
  <header
    style="border: solid 2px grey; background-color: white"
    class="flex h-16 justify-between"
  >
    <div class="flex items-center py-2 w-80 justify-center">
      <img
        class="h-full px-2"
        src="../../assets/icon-alpha.png"
        alt="Instituto Alpha"
      />
      <h3 class="text-xl font-semibold">Alpha Instituto Cubatão</h3>
    </div>
    <div class="flex">
      <nuxtLink
        class="flex items-center mx-8 text-sm/6 font-semibold"
        :to="item.to"
        v-for="item in items"
        :key="item.label"
      >
        {{ item.label }}
      </nuxtLink>
    </div>
    <div class="w-80">
      <nuxt-link to="CadastrarLogar">
        <UButton
          color="blue"
          variant="solid"
          class="my-3 w-28 h-10 fit-content flex justify-center mx-2 float-right"
        >
          Entrar
        </UButton>
      </nuxt-link>
    </div>
  </header>
</template>
