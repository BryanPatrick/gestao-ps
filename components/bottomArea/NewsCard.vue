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
    title: "",
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
    local: "SAMU",
  },
]);
</script>

<template>
  <div class="w-full my-5 text-center">
    <h2 class="text-xl font-semibold">Últimas noticias</h2>
    <div class="flex flex-col items-center relative">
      <span class="w-14 bg-teal-700 h-[3px] absolute top-0 z-10"></span>
      <span class="w-40 bg-gray-400 h-[1px] absolute top-[0.5px]"></span>
    </div>
    <p class="font-light text-xs mt-2">
      Para mais noticias clicar em saber mais
    </p>
  </div>

  <div class="py-5 mx-16">
    <article class="w-60 h-[506px] shadow-xl overflow-hidden">
      <div class="h-[40%] relative">
        <span
          class="my-3 float-right bg-white w-full text-center font-didactGothic font-bold text-teal-800"
          >Pronto Socorro Central</span
        >
        <img src="../../assets/psc.jpeg" alt="Imagem" />
      </div>
      <div class="h-[45%] p-2">
        <h3 class="text-center text-xl font-bold">
          Reforma de pronto socorro programado para 2025
        </h3>
        <p class="text-xs font-light pt-2 text-center">
          Segundo informações de funcionários as reformas previstas para o ano
          de 2025 terá inicio nos próximos meses, reforma esta que irá melhorar
          o acesso e espaços internos da unidade assim conseguindo atender
          melhor a demanda local, veja reportagem.
        </p>
      </div>
      <div class="h-[15%] flex items-center justify-center">
        <button class="w-24 h-10 rounded-md bg-teal-700 text-white font-bold">
          Saber mais
        </button>
      </div>
    </article>
  </div>

  <div class="py-5 mx-16">
    <article class="w-60 h-[506px] shadow-xl overflow-hidden">
      <div class="h-[40%] relative">
        <span
          class="my-3 float-right bg-white w-full text-center font-didactGothic font-bold text-teal-800"
          >Pronto Socorro Infantil</span
        >
        <img src="../../assets/psi.jpeg" alt="Imagem" />
      </div>
      <div class="h-[45%] p-2">
        <h3 class="text-center text-xl font-bold">
          Manutenção de infraestrutura de redes
        </h3>
        <p class="text-xs font-light pt-2 text-center">
          Estaremos realizando uma atualização em nossa rede com o intuito de
          melhorar os nossos serviços. Neste periodo teremos algumas quedas e
          lentidões que poderam impactar no serviço, neste periodo contamos com
          a compreensão de todos.
        </p>
      </div>
      <div class="h-[15%] flex items-center justify-center">
        <button class="w-24 h-10 rounded-md bg-teal-700 text-white font-bold">
          Saber mais
        </button>
      </div>
    </article>
  </div>

  <div class="py-5 mx-16">
    <article class="w-60 h-[506px] shadow-xl overflow-hidden">
      <div class="h-[40%] relative overflow-hidden">
        <span
          class="my-3 float-right bg-white w-full text-center font-didactGothic font-bold text-teal-800"
          >SAMU 192</span
        >
        <img class="h-[160px]" src="../../assets/samu2.jpeg" alt="Imagem" />
      </div>
      <div class="h-[45%] p-2">
        <h3 class="text-center text-xl font-bold">Herois entre nós</h3>
        <p class="text-xs font-light pt-2 text-center">
          Neste final de semana (11/01/2025), a nossa equipe do SAMU ganhou uma
          medalha de salvamento devido a um ato heroico onde foram salvo 4
          pessoas em um acidente de carro na rodovia dos imigrantes, ver mais...
        </p>
      </div>
      <div class="h-[15%] flex items-center justify-center">
        <button class="w-24 h-10 rounded-md bg-teal-700 text-white font-bold">
          Saber mais
        </button>
      </div>
    </article>
  </div>
</template>
