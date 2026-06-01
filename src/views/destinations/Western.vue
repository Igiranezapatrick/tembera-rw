<script setup>
import westernImg from '../../assets/lake.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Western Rwanda</h1>
          <p class="text-xl text-slate-600 leading-relaxed mb-6">Experience Lake Kivu's tranquil shores and Rwanda's cultural heritage in a calm, refined setting.</p>
          <div class="space-y-6">
            <div>
              <h3 class="font-bold text-slate-900">Lake Kivu</h3>
              <p class="text-slate-600 text-sm">Spectacular lake scenery and premium waterfront experiences.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Resort Stays</h3>
              <p class="text-slate-600 text-sm">Luxury accommodations with immersive lakeside hospitality.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Cultural Heritage</h3>
              <p class="text-slate-600 text-sm">Historic sites and reconciliation-focused tours.</p>
            </div>
          </div>
        </div>
        <div class="relative rounded-[32px] h-96 overflow-hidden shadow-lg">
          <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${westernImg})` }"></div>
          <div class="absolute inset-0 bg-slate-950/35"></div>
          <div class="relative z-10 flex h-full items-center justify-center text-white text-center px-8">
            <div>
              <p class="text-2xl font-semibold">Western Rwanda</p>
              <p class="mt-4 text-sm text-slate-100">Refined lakeside travel with historic and cultural depth.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="mb-16">
        <h2 class="text-4xl font-bold text-slate-900 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Water Sports</h3>
            <p class="text-slate-600 mb-4">Kayaking, swimming, and gentle waterside adventures with attentive support.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Sunset Cruises</h3>
            <p class="text-slate-600 mb-4">Elegant evening cruises across the lake with scenic views and local refreshments.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Cultural Tours</h3>
            <p class="text-slate-600 mb-4">Explore museums, memorials, and heritage experiences with knowledgeable local guides.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
        </div>
      </div>

      <div class="bg-slate-50 rounded-3xl p-12">
        <h2 class="text-3xl font-bold text-slate-900 mb-8 text-center">Practical Information</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Best Time to Visit</p>
            <p class="text-lg font-bold text-emerald-600">Year-round</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Lake Area</p>
            <p class="text-lg font-bold text-emerald-600">2,700 km²</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Water Temp</p>
            <p class="text-lg font-bold text-emerald-600">23–25°C</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-emerald-600">~300 km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>