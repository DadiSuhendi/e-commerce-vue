<script setup>
  import { RouterView } from 'vue-router'
  import Navbar from '@/components/Navbar.vue';
</script>

<template>
  <Navbar v-if="$route.name != 'login' && $route.name != 'register'"/>
  <div :class="($route.name == 'home' ? 'px-80' : '')">
    <RouterView />
  </div>
</template>