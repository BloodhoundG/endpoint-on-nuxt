<template>
  <div>
    {{ data }}
  </div>
</template>

<script setup lang="ts">
const { data } = await useFetch("/api/hello");
</script>

<style scoped>
div {
  display: flex;
  justify-content: center;
  font-size: 40px;
  margin: 20px 0 0;
}
</style>
