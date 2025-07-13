<script setup>
import { useRoute } from "vue-router";
const route = useRoute();
</script>

<template>
  <main style="color: #000">Todo Item {{ route.params.id }}</main>
</template>
