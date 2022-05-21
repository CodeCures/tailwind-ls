<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <main class="w-screen min-h-screen bg-gray-100 flex flex-col items-center justify-center">
    <div class="grid lg:grid-cols-2 2xl:grid-cols-5 bg-gray-50">
      <div class="px-8 py-12 max-w-sm sm:max-w-xl lg:max-w-full mx-auto xl:mr-0 rounded-xl 2xl:col-span-2">
        <div class="xl:max-w-xl space-y-6 sm:space-y-8">
          <img class="h-10" src="./assets/logo.svg" alt="logo">
          <img class="rounded-xl shadow-xl sm:h-64 sm:w-full sm:object-cover object-center lg:hidden" src="./assets/beach-work.jpg" alt="beach-work">
          <div class="space-y-3 md:space-y-8">
            <h1 class="text-xl sm:text-4xl lg:text-3xl xl:text-4xl font-bold text-gray-900 leading-none">You can work from anywhere. 
              <br class="hidden lg:inline">
              <span class="text-indigo-600">Take advantage of it.</span></h1>
            <p class="text-gray-600 leading-tight sm:text-lg"> Workcation helps you find work-friendly rentals in beautiful locations so you can enjoy some nice weather even when you're not on vacation.</p>
            <a class="inline-block bg-indigo-500 text-white text-xs sm:text-base tracking-wider uppercase font-semibold rounded-lg px-4 py-2 shadow-lg hover:bg-indigo-600 focus:outline-none focus:ring-2 focus:ring-indigo-600 focus:ring-offset-2" href="javascript:void(0)">Book Your Escape</a>
          </div>
        </div>
      </div>
      <div class="hidden lg:block relative 2xl:col-span-3">
        <img class="absolute inset-0 w-full h-full object-cover object-center" src="./assets/beach-work.jpg" alt="beach-work">
      </div>
    </div>
  </main>
</template>

