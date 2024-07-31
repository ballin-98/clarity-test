<script setup lang="ts"></script>

<template>
  <div class="app-container">
    <div class="button-container">
      <button class="app-btn">Send Email</button>
      <button class="app-btn">Hack User</button>
      <button class="app-btn">Buy Tickets</button>
    </div>
  </div>
</template>

<style scoped>
.app-container {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.button-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
  justify-content: center;
  align-items: center;
  flex: 1;
}

.app-btn {
  width: 400px;
  height: 100px;
}
</style>
