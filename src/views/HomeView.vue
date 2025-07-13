<script setup></script>

<template>
  <main style="color: #000; padding: 2rem">
    <input type="text" placeholder="Enter Search Here!..." />
    <div class="group-card">
      <div class="card-item">
        <h2>SkyBlack</h2>
        <i>Hello</i>
      </div>
      <div class="card-item">
        <h2>SkyBlue</h2>
        <i>Hello</i>
      </div>
    </div>
  </main>
</template>

<style scoped>
input {
  width: 100%;
  padding: 0.6rem 1.2rem;
  border-radius: 50px;
  border: none;
  outline: none;
  background: #ededed;
}

.group-card {
  margin-top: 1.5rem;
  display: flex;
  flex-direction: column;
  row-gap: 1.5rem;
}

.card-item {
  border-radius: 10px;
  background: #324558;
  color: #fff;
  cursor: pointer;
  padding: 0.8rem 1rem;
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.15);
}

.card-item:hover {
  background: #243241;
}
</style>
