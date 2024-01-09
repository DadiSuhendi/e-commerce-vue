<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import Navbar from '@/components/Home/Navbar.vue';
</script>

<template>
  <Navbar/>
  <div class="px-80">
    <RouterView />
  </div>
</template>