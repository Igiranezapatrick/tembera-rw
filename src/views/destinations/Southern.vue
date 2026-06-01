<script setup>
import southernImg from '../../assets/kivu.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Southern Rwanda</h1>
          <p class="text-xl text-slate-600 leading-relaxed mb-6">Discover Nyungwe Forest, tea plantations, and Lake Kivu from Rwanda's lush southern region.</p>
          <div class="space-y-6">
            <div>
              <h3 class="font-bold text-slate-900">Nyungwe Forest</h3>
              <p class="text-slate-600 text-sm">Ancient rainforest with exceptional biodiversity.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Tea Plantations</h3>
              <p class="text-slate-600 text-sm">Rolling green hills with premium tea estates.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Lake Kivu</h3>
              <p class="text-slate-600 text-sm">Luxury lakeside travel and waterside retreats.</p>
            </div>
          </div>
        </div>
        <div class="relative rounded-[32px] h-96 overflow-hidden shadow-lg">
          <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${southernImg})` }"></div>
          <div class="absolute inset-0 bg-slate-950/35"></div>
          <div class="relative z-10 flex h-full items-center justify-center text-white text-center px-8">
            <div>
              <p class="text-2xl font-semibold">Southern Rwanda</p>
              <p class="mt-4 text-sm text-slate-100">A refined escape for forest, lake, and boutique travel.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="mb-16">
        <h2 class="text-4xl font-bold text-slate-900 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Canopy Walks</h3>
            <p class="text-slate-600 mb-4">Elevated forest experiences with premium guided tours.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Lake Activities</h3>
            <p class="text-slate-600 mb-4">Water sports and relaxation at Lake Kivu's shorelines.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Chimp Trekking</h3>
            <p class="text-slate-600 mb-4">Explore primate habitats with sustainable wildlife tours.</p>
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
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Altitude</p>
            <p class="text-lg font-bold text-emerald-600">1,600–2,950m</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Temperature</p>
            <p class="text-lg font-bold text-emerald-600">18–25°C</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-emerald-600">~200 km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>