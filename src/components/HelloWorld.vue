<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="max-w-4xl mx-auto px-6 text-center">
    <h1 class="text-5xl font-bold text-white mb-12">{{ msg }}</h1>

    <div class="bg-gray-800 rounded-lg p-8 mb-8 border border-gray-700">
      <button 
        type="button" 
        @click="count++" 
        class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition-colors duration-200 mb-4"
      >
        count is {{ count }}
      </button>
      <p class="text-gray-300 mt-4">
        Edit
        <code class="bg-gray-700 text-cyan-400 px-2 py-1 rounded text-sm mx-1">components/HelloWorld.vue</code> 
        to test HMR
      </p>
    </div>

    <p class="text-gray-300 mb-4">
      Check out
      <a 
        href="https://vuejs.org/guide/quick-start.html#local" 
        target="_blank"
        class="text-blue-400 hover:text-blue-300 underline transition-colors duration-200"
      >
        create-vue
      </a>, the official Vue + Vite starter
    </p>
    
    <p class="text-gray-300 mb-4">
      
      Learn more about IDE Support for Vue in the
       <a
        href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
        target="_blank"
        class="text-blue-400 hover:text-blue-300 underline transition-colors duration-200"
      >
        Vue Docs Scaling up Guide
      </a>.
    </p>
    
    <p class="text-gray-500 mt-8">Click on the Vite and Vue logos to learn more</p>
  </div>
</template>