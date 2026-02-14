<script setup lang="ts">
// Dank Nuxt & TS brauchen wir hier für den Anfang fast nichts importieren!
const message = ref("Nuxt, Tailwind & TS laufen!")
</script>
 
<template>
  <div class="h-screen bg-slate-900 flex items-center justify-center">
    <div class="p-8 bg-white rounded-2xl shadow-xl text-center">
      <h1 class="text-3xl font-bold text-blue-600 mb-4">{{ message }}</h1>
      <UButton color="blue" variant="solid" @click="message = 'Es funktioniert perfekt!'">
       Hallo
      </UButton>
    </div>
  </div>
</template>
