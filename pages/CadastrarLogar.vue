<script setup></script>

<template>
  <div class="flex justify-center items-center h-[100vh]">
    <div
      class="w-72 h-64 flex flex-col items-center"
      style="border: solid 2px grey"
    >
      <div class="my-2">
        <label for="">Nome: </label>
        <input type="text" placeholder="teste" style="border: solid 2px grey" />
      </div>
      <div class="my-2">
        <label for="">CPF: </label>
        <input type="text" placeholder="teste" style="border: solid 2px grey" />
      </div>
      <div class="my-2">
        <label for="">Email: </label>
        <input type="text" placeholder="teste" style="border: solid 2px grey" />
      </div>
      <div class="my-2">
        <label for="">Senha: </label>
        <input type="text" placeholder="teste" style="border: solid 2px grey" />
      </div>
      <button class="w-32 h-12 rounded-xl" style="background-color: green">
        Confirmar
      </button>
    </div>
  </div>
</template>
