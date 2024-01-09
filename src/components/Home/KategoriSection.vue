<script setup>
    import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="pt-10">
        <span class="text-2xl font-bold">
            Kategori Pilihan
            <RouterLink to="/" class="text-lg text-[#3468C0]">Lihat Semua Kategori</RouterLink>
        </span>
        <div class="flex gap-4">
        <RouterLink to="/" class="w-44 h-44 block">
            <div class="w-full h-full bg-black mt-4 relative">
            <p class="absolute text-2xl font-bold flex w-full justify-center h-full items-center">BAJU</p>
            <img src="https://images.unsplash.com/photo-1620799140408-edc6dcb6d633?q=80&w=1972&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Kategori Baju" class="w-full h-full object-cover">
            </div>
        </RouterLink>
        <RouterLink to="/" class="w-44 h-44 block">
            <div class="w-full h-full bg-black mt-4 relative">
            <p class="absolute text-2xl font-bold flex w-full justify-center h-full items-center">SEPATU</p>
            <img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Kategori Sepatu" class="w-full h-full object-cover">
            </div>
        </RouterLink>
        <RouterLink to="/" class="w-44 h-44 block">
            <div class="w-full h-full bg-black mt-4 relative">
            <p class="absolute text-2xl font-bold flex w-full justify-center h-full items-center">SEPATU</p>
            <img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Kategori Sepatu" class="w-full h-full object-cover">
            </div>
        </RouterLink>
        <RouterLink to="/" class="w-44 h-44 block">
            <div class="w-full h-full bg-black mt-4 relative">
            <p class="absolute text-2xl font-bold flex w-full justify-center h-full items-center">SEPATU</p>
            <img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Kategori Sepatu" class="w-full h-full object-cover">
            </div>
        </RouterLink>
        </div>
    </div>
</template>