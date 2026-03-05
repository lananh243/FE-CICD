<template>
  <header class="header">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </header>
</template>

<style>
.header {
  padding: 15px;
  background: #222;
  display: flex;
  gap: 20px;
}

a {
  color: white;
  text-decoration: none;
}
</style>