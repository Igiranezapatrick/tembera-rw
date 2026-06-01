<script setup>
import { ref } from 'vue'
</script>

<template>
  <section class="py-12">
    <div class="max-w-4xl mx-auto">
      <div class="text-center mb-12">
        <h2 class="text-4xl font-bold text-gray-800 mb-4">Welcome to Our Platform</h2>
        <p class="text-xl text-gray-600 mb-8">Discover the best experiences in Rwanda with our expert guides and comprehensive travel services</p>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-gradient-to-br from-blue-50 to-indigo-100 rounded-lg p-8 text-center">
          <div class="text-5xl mb-4">🌍</div>
          <h3 class="text-xl font-bold text-gray-800 mb-3">Global Reach</h3>
          <p class="text-gray-700">Connect with travelers from around the world and share unforgettable Rwandan experiences</p>
        </div>
        
        <div class="bg-gradient-to-br from-green-50 to-emerald-100 rounded-lg p-8 text-center">
          <div class="text-5xl mb-4">🤝</div>
          <h3 class="text-xl font-bold text-gray-800 mb-3">Expert Support</h3>
          <p class="text-gray-700">Our experienced team is always ready to assist with planning your perfect Rwandan adventure</p>
        </div>
        
        <div class="bg-gradient-to-br from-yellow-50 to-orange-100 rounded-lg p-8 text-center">
          <div class="text-5xl mb-4">⭐</div>
          <h3 class="text-xl font-bold text-gray-800 mb-3">Premium Quality</h3>
          <p class="text-gray-700">Experience world-class service and accommodations throughout your journey in Rwanda</p>
        </div>
      </div>
    </div>
  </section>
</template>