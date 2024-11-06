<script setup>
let escalaBody = reactive([
  {
    id: 1,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 2,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 3,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 4,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 5,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 6,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 7,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 8,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 9,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 10,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 11,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 12,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 13,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 14,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 15,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 16,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 17,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 18,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 19,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 20,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 21,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 22,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 23,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 24,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 25,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 26,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 27,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 28,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: 29,
    name1: "Bryan Patrick",
    time1: "07:00 às 19:00",
    name2: "Elmo",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(227, 240, 215)",
    color2: "background-color: rgb(229, 213, 230)",
  },
  {
    id: 30,
    name1: "Luiz Felipe",
    time1: "07:00 às 19:00",
    name2: "Vinicius",
    time2: "19:00 às 07:00",
    name3: "Cristiano Xavier",
    folga: "(Folga)",
    banco: "(Banco)",
    color1: "background-color: rgb(252, 229, 212)",
    color2: "background-color: rgb(225, 240, 200)",
  },
  {
    id: "1",
    color1: "background-color: white;",
    color2: "background-color: white;",
    color3: "background-color: white;",
  },
  {
    id: "2",
    color1: "background-color: white;",
    color2: "background-color: white;",
    color3: "background-color: white;",
  },
  {
    id: "3",
    color1: "background-color: white;",
    color2: "background-color: white;",
    color3: "background-color: white;",
  },
  {
    id: "4",
    color1: "background-color: white;",
    color2: "background-color: white;",
    color3: "background-color: white;",
  },
  {
    id: "5",
    color1: "background-color: white;",
    color2: "background-color: white;",
    color3: "background-color: white;",
  },
]);
</script>

<template>
  <div>
    <Header class="fixed w-full" />
    <div class="flex h-screen">
      <aside class="w-[15%] pt-20 p-5">
        <span>Escalas</span>
        <div class="my-2">
          <ul>
            <li class="px-4">T.I</li>
            <li class="px-7"><small>Escala mensal</small></li>
            <li class="px-7"><small>Escala semanal</small></li>
            <li class="px-7"><small>Escala diária</small></li>
          </ul>
        </div>
        <div class="my-2">
          <ul>
            <li class="px-4">ENFERMAGEM</li>
            <li class="px-7"><small>Mensal</small></li>
            <li class="px-7"><small>Semanal</small></li>
            <li class="px-7"><small>Diário</small></li>
          </ul>
        </div>
        <span>Relatórios</span>
        <div class="my-2">
          <ul>
            <li class="px-4">T.I</li>
            <li class="px-7"><small>Mensal</small></li>
            <li class="px-7"><small>Semanal</small></li>
            <li class="px-7"><small>Diário</small></li>
          </ul>
        </div>
        <span>Relatórios</span>
        <div class="my-2">
          <ul>
            <li class="px-4">T.I</li>
            <li class="px-7"><small>Mensal</small></li>
            <li class="px-7"><small>Semanal</small></li>
            <li class="px-7"><small>Diário</small></li>
          </ul>
        </div>
      </aside>
      <section class="w-full p-5 pt-20">
        <div
          class="grid grid-cols-7 grid-rows-4 gap-1"
          style="background-color: black; border: 4px solid black"
        >
          <span
            class="w-full h-40 grid grid-rows-9 text-center"
            style="background-color: green"
            v-for="item in escalaBody"
          >
            <small style="background-color: white">{{ item.id }}</small>
            <small :style="item.color1">{{ item.time1 }}</small>
            <small :style="item.color1">{{ item.name1 }}</small>
            <small :style="item.color1"></small>
            <small style="background-color: white"></small>
            <small :style="item.color2">{{ item.time2 }}</small>
            <small :style="item.color2">{{ item.name2 }}</small>
            <small :style="item.color2"></small>
            <small style="background-color: white"></small>
          </span>
        </div>
      </section>
      <aside class="w-[21%]">
        <div class="w-64 mt-20" style="border: 2px solid black">
          <h3 class="text-center">DIAS TRABALHADOS / FOLGA</h3>
          <div
            class="h-fit grid grid-cols-5 gap-x-0.5"
            style="background-color: black; border-top: 2px solid black"
          >
            <span
              class="teste flex items-center justify-center py-2"
              style="background-color: rgb(252, 229, 212)"
              >Luiz Felipe</span
            >
            <span
              class="teste flex items-center justify-center py-2"
              style="background-color: rgb(225, 240, 200)"
              >Vinicius</span
            >
            <span
              class="teste flex items-center justify-center py-2"
              style="background-color: rgb(227, 240, 215)"
              >Bryan</span
            >
            <span
              class="teste flex items-center justify-center py-2"
              style="background-color: rgb(229, 213, 230)"
              >Elmo</span
            >
            <span
              class="teste flex items-center justify-center py-2"
              style="background-color: rgb(249, 218, 217)"
              >Cristiano</span
            >
          </div>
          <div
            class="h-24 grid grid-cols-5 gap-x-0.5"
            style="background-color: black; border-top: 2px solid black"
          >
            <div
              class="flex flex-col justify-center items-center text-center"
              style="background-color: rgb(252, 229, 212)"
            >
              <small>14</small>
              <small>DIAS</small>
            </div>
            <div
              class="flex flex-col justify-center items-center text-center"
              style="background-color: rgb(225, 240, 200)"
            >
              <small>14</small>
              <small>DIAS</small>
            </div>
            <div
              class="flex flex-col justify-center items-center text-center"
              style="background-color: rgb(227, 240, 215)"
            >
              <small>14</small>
              <small>DIAS</small>
            </div>
            <div
              class="flex flex-col justify-center items-center text-center"
              style="background-color: rgb(229, 213, 230)"
            >
              <small>14</small>
              <small>DIAS</small>
            </div>
            <div
              class="flex flex-col justify-center items-center text-center"
              style="background-color: rgb(249, 218, 217)"
            >
              <small>14</small>
              <small>DIAS</small>
            </div>
          </div>
          <div
            class="h-fit grid grid-cols-5 gap-x-0.5"
            style="background-color: black; border-top: 2px solid black"
          >
            <small
              class="text-xs text-center"
              style="background-color: rgb(252, 229, 212)"
              >FOLGA</small
            >
            <small
              class="text-xs text-center"
              style="background-color: rgb(225, 240, 200)"
              >FOLGA</small
            >
            <small
              class="text-xs text-center"
              style="background-color: rgb(227, 240, 215)"
              >FOLGA</small
            >
            <small
              class="text-xs text-center"
              style="background-color: rgb(229, 213, 230)"
              >FOLGA</small
            >
            <small
              class="text-xs text-center"
              style="background-color: rgb(249, 218, 217)"
              >FOLGA</small
            >
          </div>
          <div
            class="h-12 grid grid-cols-5 gap-x-0.5"
            style="background-color: black; border-top: 2px solid black"
          >
            <span
              class="flex justify-center items-center"
              style="background-color: rgb(252, 229, 212)"
              >2</span
            >
            <span
              class="flex justify-center items-center"
              style="background-color: rgb(225, 240, 200)"
              >2</span
            >
            <span
              class="flex justify-center items-center"
              style="background-color: rgb(227, 240, 215)"
              >2</span
            >
            <span
              class="flex justify-center items-center"
              style="background-color: rgb(229, 213, 230)"
              >2</span
            >
            <span
              class="flex justify-center items-center"
              style="background-color: rgb(249, 218, 217)"
              >2</span
            >
          </div>
        </div>
      </aside>
    </div>
  </div>
</template>

<style scoped>
.teste {
  writing-mode: vertical-rl;
  text-orientation: upright;
}
</style>
