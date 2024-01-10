<script setup>
import { RouterLink } from 'vue-router'
</script>
<template>
  <header>
    <div class="w-full h-20 bg-white text-white flex items-center justify-between px-72 shadow-md">
      <!-- Left Side -->
      <div class="flex items-center gap-20">
        <RouterLink to="/" class="text-[#3468C0] text-lg font-bold">{{ this.AppName }}</RouterLink>
        <!-- component -->
        <div class='max-w-md mx-auto w-[30rem]'>
            <div class="relative flex items-center w-full h-9 rounded-lg bg-white overflow-hidden border">
                <div class="grid place-items-center h-full w-12 text-gray-300">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                </div>

                <input
                class="peer h-full w-full outline-none text-sm text-gray-700 pr-2"
                type="text"
                id="search"
                placeholder="Search something.." /> 
            </div>
        </div>
      </div>
      <!-- Right Side -->
      <div class="flex gap-3 items-center">
        <RouterLink to="/chart">
          <i class="fa-solid fa-cart-shopping text-black text-xl mr-5"></i>
        </RouterLink>
        <RouterLink to="/login" class="bg-[#3468C0] px-5 py-1.5 rounded-full">Login</RouterLink>
        <RouterLink to="/about" class="px-5 py-1.5 rounded-full border text-black">Sign up</RouterLink>
      </div>
    </div>
  </header>
</template>