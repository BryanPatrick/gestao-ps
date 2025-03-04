<script setup lang="ts">
import { SidebarProvider, SidebarTrigger } from "@/components/ui/sidebar";
import AppSidebar from "@/components/AppSidebar.vue";
import Escala from "./escala.vue";
</script>

<template>
  <SidebarProvider>
    <AppSidebar />
    <main class="flex flex-col w-full">
      <SidebarTrigger />
      <Escala />
    </main>
  </SidebarProvider>
</template>
