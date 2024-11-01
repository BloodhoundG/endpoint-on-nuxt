<template>
  <div>
    <NuxtPage />
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
const { data } = await useFetch("/api/hello");
</script>
