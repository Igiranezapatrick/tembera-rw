<script setup>
import cityImg from '../../assets/image.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Kigali City</h1>
          <p class="text-xl text-slate-600 leading-relaxed mb-6">Rwanda's vibrant capital blends modern development with rich cultural heritage, offering museums, markets, dining, and international hospitality.</p>
          <div class="space-y-6">
            <div>
              <h3 class="font-bold text-slate-900">Modern Infrastructure</h3>
              <p class="text-slate-600 text-sm">Clean, organized, and well-developed city amenities.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">World-Class Dining</h3>
              <p class="text-slate-600 text-sm">International and local cuisine presented at premium venues.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Business & Culture</h3>
              <p class="text-slate-600 text-sm">A compelling destination for conferences, culture, and curated city experiences.</p>
            </div>
          </div>
        </div>
        <div class="relative rounded-[32px] h-96 overflow-hidden shadow-lg">
          <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${cityImg})` }"></div>
          <div class="absolute inset-0 bg-slate-950/35"></div>
          <div class="relative z-10 flex h-full items-center justify-center text-white text-center px-8">
            <div class="text-center max-w-xs">
              <p class="text-xl font-semibold">Kigali</p>
              <p class="mt-4 text-sm text-slate-100">A modern African capital with refined urban appeal.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="mb-16">
        <h2 class="text-4xl font-bold text-slate-900 mb-8 text-center">Top Attractions</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Genocide Memorial</h3>
            <p class="text-slate-600 mb-4">A moving tribute and historic site offering deep insights into Rwanda's journey and reconciliation.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Art & Culture</h3>
            <p class="text-slate-600 mb-4">Explore galleries, craft markets, and cultural centers celebrating Rwanda's creative heritage.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Dining & Hospitality</h3>
            <p class="text-slate-600 mb-4">Celebrate exceptional dining across local and international cuisine in Kigali's refined restaurant scene.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">City Tours</h3>
            <p class="text-slate-600 mb-4">Guided tours of landmarks, neighborhoods, and cultural destinations with expert local hosts.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Shopping & Crafts</h3>
            <p class="text-slate-600 mb-4">Discover premium textiles, artisanal crafts, and modern boutiques in Kigali's shopping districts.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Urban Parks</h3>
            <p class="text-slate-600 mb-4">Relax in well-maintained green spaces that offer calm and scenic escapes inside the city.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
        </div>
      </div>

      <div class="bg-slate-50 rounded-3xl p-12">
        <h2 class="text-3xl font-bold text-slate-900 mb-8 text-center">Practical Information</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Population</p>
            <p class="text-lg font-bold text-emerald-600">1.2M</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Altitude</p>
            <p class="text-lg font-bold text-emerald-600">1,567m</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Climate</p>
            <p class="text-lg font-bold text-emerald-600">Temperate</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Airport</p>
            <p class="text-lg font-bold text-emerald-600">10 km from city</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>