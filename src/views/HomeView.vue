<template>
  <div class="min-h-screen bg-gray-900">
    <!-- Content -->
    <div class="flex justify-center items-center gap-8 py-12 pt-20">
      <a 
        href="https://vite.dev" 
        target="_blank"
        class="h-24 p-6 transition-all duration-300 hover:drop-shadow-[0_0_2em_rgba(100,108,255,0.67)] hover:scale-110"
      >
        <img src="/vite.svg" class="h-full" alt="Vite logo" />
      </a>
      <a 
        href="https://vuejs.org/" 
        target="_blank"
        class="h-24 p-6 transition-all duration-300 hover:drop-shadow-[0_0_2em_rgba(66,184,131,0.67)] hover:scale-110"
      >
        <img src="../assets/vue.svg" class="h-full" alt="Vue logo" />
      </a>
    </div>
    <HelloWorld msg="Vite + Vue" />
  </div>
</template>

<script setup>
import HelloWorld from '../components/HelloWorld.vue'
</script>