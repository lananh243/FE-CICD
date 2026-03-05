<template>
  <AppHeader />
  <div class="container">
    <router-view />
  </div>
</template>

<script setup>
import AppHeader from './components/AppHeader.vue';

</script>

<style>
.container {
  padding: 20px;
}
</style>