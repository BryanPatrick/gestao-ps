<script setup>
let maqueiroOpen = ref(false);
let manutencaoOpen = ref(false);
let tiOpen = ref(false);

function openMaqueiro() {
  maqueiroOpen.value = true;
  manutencaoOpen.value = false;
  tiOpen.value = false;
}
function openManutencao() {
  maqueiroOpen.value = false;
  manutencaoOpen.value = true;
  tiOpen.value = false;
}
function openTi() {
  maqueiroOpen.value = false;
  manutencaoOpen.value = false;
  tiOpen.value = true;
}

const setorItems = reactive([
  {
    label: "Recepção",
    local: "PSC",
  },
  {
    label: "Recepção",
    local: "PSI",
  },
  {
    label: "Triagem",
    local: "PSC",
  },
  {
    label: "Triagem",
    local: "PSI",
  },
  {
    label: "Clínico",
    local: "PSC",
  },
  {
    label: "Pediatra",
    local: "PSI",
  },
  {
    label: "Emergência",
    local: "PSC",
  },
  {
    label: "Semi intensivo/Repouso",
    local: "PSC",
  },
  {
    label: "Semi intensivo/Repouso",
    local: "PSI",
  },
  {
    label: "Cirurgião Geral",
    local: "PSC",
  },
  {
    label: "Cirurgião Plástico",
    local: "PSC",
  },
  {
    label: "Cirurgião Dentista",
    local: "PSC",
  },
  {
    label: "Medicação",
    local: "PSC",
  },
  {
    label: "Medicação",
    local: "PSI",
  },
  {
    label: "Assistente Social",
    local: "PSC",
  },
  {
    label: "Assistente Social",
    local: "PSI",
  },
  {
    label: "Supervisão",
    local: "PSC",
  },
  {
    label: "Administrativo",
    local: "PSC",
  },
  {
    label: "CCIH",
    local: "PSC",
  },
  {
    label: "Recursos Humanos",
    local: "PSC",
  },
  {
    label: "Ortopedia",
    local: "PSC",
  },
  {
    label: "Retorno Trauma",
    local: "PSC",
  },
]);
const unidadeItems = reactive([
  {
    label: "PSC",
  },
  {
    label: "PSI",
  },
]);
const motivoItems = reactive([
  {
    label: "Internet",
  },
  {
    label: "Impressora",
  },
  {
    label: "Computador",
  },
  {
    label: "Periférios (mouse, teclado, etc...)",
  },
  {
    label: "Outros motivos (descreva a seguir)",
  },
]);
</script>

<template>
  <div>
    <Header />
    <h3 class="text-center my-5 font-bold text-4xl">
      Escolha o tipo de chamado que deseja realizar
    </h3>

    <div class="flex justify-center">
      <button
        @click="openMaqueiro"
        class="w-72 h-20 mx-5 text-lg rounded-xl"
        style="background-color: green"
      >
        Maqueiro
      </button>
      <button
        @click="openManutencao"
        class="w-72 h-20 mx-5 text-lg rounded-xl"
        style="background-color: green"
      >
        Manutenção
      </button>
      <button
        @click="openTi"
        class="w-72 h-20 mx-5 text-lg rounded-xl"
        style="background-color: green"
      >
        T.I
      </button>
    </div>

    <div v-show="maqueiroOpen">Chamado 1</div>

    <div v-show="manutencaoOpen">Chamado 2</div>

    <div v-show="tiOpen" class="my-5 flex justify-center">
      <div class="w-[31.25rem] px-20 bord">
        <h3 class="my-5 font-bold text-xl text-center">
          Chamado para o setor de T.I
        </h3>
        <div class="flex flex-col">
          <label class="flex-initial">
            <small>Unidade (PSC ou PSI)</small>
          </label>
          <select class="text-center w-full h-9 bord">
            <option value="" selected disabled>Selecionar</option>
            <option
              v-for="item in unidadeItems"
              :key="item.label"
              :value="item.label"
            >
              {{ item.label }}
            </option>
          </select>
        </div>
        <div class="flex flex-col">
          <label class="flex-initial">
            <small>Setor</small>
          </label>
          <select class="text-center w-full h-9 bord">
            <option value="" selected disabled>Selecionar</option>
            <option
              v-for="item in setorItems"
              :key="item.label"
              :value="item.label"
            >
              {{ item.label }}
            </option>
          </select>
        </div>
        <div class="flex flex-col">
          <label class="flex-initial">
            <small>Motivo do chamado</small>
          </label>
          <select class="text-center w-full h-9 bord">
            <option value="" selected disabled>Selecionar</option>
            <option
              v-for="item in motivoItems"
              :key="item.label"
              :value="item.label"
            >
              {{ item.label }}
            </option>
          </select>
        </div>
        <div class="flex flex-col">
          <label class="flex-initial">
            <small>Descrição</small>
          </label>
          <textarea class="w-full h-20 bord" name="" id=""></textarea>
        </div>
        <div class="w-full flex justify-end">
          <button
            class="w-32 h-12 m-5 rounded-xl"
            style="background-color: green"
          >
            Confirmar
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bord {
  border: 2px solid grey;
  border-radius: 8px;
}
</style>
