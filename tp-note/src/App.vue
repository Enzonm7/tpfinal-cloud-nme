<script setup>
  const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
  const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
    <header>
    <p class="name">Nom : Enzo NZENGUE MAYILA</p>
    <p>Date : {{ today }}</p>
    <p>Build : {{ buildId }}</p>
  </header>
</template>

<style scoped>
.name{
  color: goldenrod;
  font-size: larger;
}
</style>