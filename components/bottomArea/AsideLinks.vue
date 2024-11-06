<script setup></script>

<template>
  <aside
    style="border: 2px solid gray"
    class="flex flex-col w-60 rounded-xl px-5 my-5 font-semibold border-slate-500"
  >
    <h3 class="my-4 text-center font-size font-bold text-lg">Links úteis</h3>
    <nuxt-link
      class="flex items-center text-left"
      to="http://www.cmdpro.com.br/cubatao/login"
      target="_blank"
    >
      <img
        class="mx-3 my-2"
        src="../../assets/icon/MedicalIconIHealthServices.svg"
        alt="Site cmdpro"
      />
      <span>CMDPRO</span>
    </nuxt-link>
    <nuxt-link
      class="flex items-center text-left"
      to="https://biomega.lisnet.com.br/laudos/#"
      target="_blank"
    >
      <img
        class="mx-3 my-2"
        src="../../assets/icon/MedicalIconILaboratory.svg"
        alt="Site biomega"
      />
      <span>BIOMEGA</span>
    </nuxt-link>
    <nuxt-link
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
    </nuxt-link>
    <nuxt-link
      class="flex items-center"
      to="https://laudos.mobilemed.com.br/login"
      target="_blank"
    >
      <img
        class="mx-3 my-2"
        src="../../assets/icon/MedicalIconIImagingRootCategory.svg"
        alt="Site raio x laudo"
      />
      <span>RAIO X - Laudo</span>
    </nuxt-link>
    <nuxt-link
      class="flex items-center"
      to="https://www.siresp.saude.sp.gov.br/"
      target="_blank"
    >
      <img
        class="mx-3 my-2"
        src="../../assets/icon/MedicalIconIIntensiveCare.svg"
        alt="Site raio x laudo"
      />
      <span>CROSS</span>
    </nuxt-link>
    <nuxt-link
      class="flex items-center"
      to="https://cubatao.ssosamu.com:8090/account/login"
      target="_blank"
    >
      <img
        class="mx-3 my-2"
        src="../../assets/icon/MedicalIconIAmbulance.svg"
        alt="Site raio x laudo"
      />
      <span>SAMU</span>
    </nuxt-link>
  </aside>
</template>
