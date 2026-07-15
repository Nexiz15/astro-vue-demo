<script setup lang="ts"></script>

<template>
  <header>
    <a href="/">Home</a>
    <a href="/about">About</a>
  </header>
</template>

<style scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding: 20px 50px 20px 50px;
  background: rgb(2 112 67 / 0.31);
  display: flex;
  gap: 16px;
  box-sizing: border-box;
}

a {
  color: black;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
