<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <main class="w-screen min-h-screen bg-gray-100 flex flex-col items-center justify-center">
    <div class="p-2 max-w-sm flex flex-col space-y-6 rounded-xl">
        <div> 
          <img class="h-10" src="./assets/logo.svg" alt="logo">
        </div>
        <div>
          <img class="rounded-xl shadow-xl" src="./assets/beach-work.jpg" alt="beach-work">
        </div>
        <div class="w-full min-h-32 space-y-3">
          <h1 class="text-2xl font-bold text-gray-900 leading-none">You can work from anywhere. <span class="text-indigo-600">Take advantage of it.</span></h1>
          <p class="text-gray-600 leading-tight"> Workcation helps you find work-friendly rentals in beautiful locations so you can enjoy some nice weather even when you're not on vacation.</p>
          <a class="inline-block bg-indigo-500 text-white text-xs tracking-wider uppercase font-semibold rounded-lg px-4 py-2 shadow-lg hover:bg-indigo-600 focus:outline-none focus:ring-2 focus:ring-indigo-600 focus:ring-offset-2" href="javascript:void(0)">Book Your Escape</a>
        </div>
    </div>
  </main>
</template>

