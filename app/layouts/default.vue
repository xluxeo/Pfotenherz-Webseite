<template>
  <div class="min-h-screen bg-gray-50">
    <AppHeader>
        <AppNavigation />
    </AppHeader>
    <main class="p-6">
      <slot />
    </main>
    <AppFooter />
  </div>
</template>

<script setup lang="ts">
// default.vue: Wird für alle Seiten genutzt, die kein eigenes layout angeben.
// <slot /> = Platzhalter für den Inhalt der jeweiligen Seite (NuxtPage)
</script>
