<script setup></script>

<template>
  <aside class="flex flex-col w-60 rounded-xl px-5 my-5 font-semibold">
    <h3
      class="my-4 font-didactGothic text-center font-size font-bold text-lg text-teal-800"
    >
      Links úteis
    </h3>
    <nuxt-link
      class="flex items-center text-left"
      to="http://www.cmdpro.com.br/cubatao/login"
      target="_blank"
    >
      <img
        class="mx-3 my-2 w-[20%]"
        src="../../assets/icone-medico.png"
        alt="Site cmdpro"
      />
      <span class="text-gray-500">CMDPRO</span>
    </nuxt-link>
    <nuxt-link
      class="flex items-center text-left"
      to="https://biomega.lisnet.com.br/laudos/#"
      target="_blank"
    >
      <img
        class="mx-3 my-2 w-[20%]"
        src="../../assets/biomega.png"
        alt="Site biomega"
      />
      <span class="text-gray-500">BIOMEGA</span>
    </nuxt-link>
    <!-- <nuxt-link
      class="flex items-center text-left"
      to="http://hmcubatao.egecloud.com.br:1500/#/login"
      target="_blank"
    >
      <img
        class="mx-3 my-2"
        src="../../assets/icon/MedicalIconIRadiology.svg"
        alt="Site raio x"
      />
      <span>RAIO X - Imagens</span>
    </nuxt-link> -->
    <nuxt-link
      class="flex items-center"
      to="https://laudos.mobilemed.com.br/login"
      target="_blank"
    >
      <img
        class="mx-2 my-2 w-[23.5%]"
        src="../../assets/mobilemed.png"
        alt="Site raio x laudo"
      />
      <span class="text-gray-500">RAIO X</span>
    </nuxt-link>
    <nuxt-link
      class="flex items-center"
      to="https://www.siresp.saude.sp.gov.br/"
      target="_blank"
    >
      <img
        class="mx-3 my-2 w-[20%]"
        src="../../assets/cross2.jpeg"
        alt="Site raio x laudo"
      />
      <span class="text-gray-500">CROSS - SIRESP</span>
    </nuxt-link>
    <nuxt-link
      class="flex items-center"
      to="https://cubatao.ssosamu.com:8090/account/login"
      target="_blank"
    >
      <img
        class="mx-3 my-2 w-[20%]"
        src="../../assets/samu.png"
        alt="Site raio x laudo"
      />
      <span class="text-gray-500">SAMU 192</span>
    </nuxt-link>
  </aside>
</template>
