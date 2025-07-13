<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header>
    <img
      class="logo"
      width="60"
      height="60"
      src="@/assets/logo.svg"
      alt="Vue Logo"
    />
    <nav>
      <RouterLink to="/">
        <div class="btn-main">Home</div>
      </RouterLink>
      <RouterLink to="/create">
        <div class="btn-action">Create</div>
      </RouterLink>
    </nav>
  </header>
  <router-view></router-view>
</template>

<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.4rem 2rem;
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.15);
}

nav {
  display: flex;
  column-gap: 1rem;
}
</style>
