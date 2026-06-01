<script setup>
import easternImg from '../../assets/park.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Eastern Rwanda</h1>
          <p class="text-xl text-slate-600 leading-relaxed mb-6">Discover Akagera National Park, Rwanda's largest protected savanna, and experience premier wildlife and wilderness travel.</p>
          <div class="space-y-6">
            <div>
              <h3 class="font-bold text-slate-900">Safari Excellence</h3>
              <p class="text-slate-600 text-sm">Big Five game drives with professional guides.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Savanna Landscapes</h3>
              <p class="text-slate-600 text-sm">Expansive grasslands and scenic lakeside views.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Wildlife Diversity</h3>
              <p class="text-slate-600 text-sm">More than 500 species supported by responsible conservation.</p>
            </div>
          </div>
        </div>
        <div class="relative rounded-[32px] h-96 overflow-hidden shadow-lg">
          <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${easternImg})` }"></div>
          <div class="absolute inset-0 bg-slate-950/35"></div>
          <div class="relative z-10 flex h-full items-center justify-center text-white text-center px-8">
            <div>
              <p class="text-2xl font-semibold">Eastern Rwanda</p>
              <p class="mt-4 text-sm text-slate-100">A premium safari destination with refined wilderness travel.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="mb-16">
        <h2 class="text-4xl font-bold text-slate-900 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Game Drives</h3>
            <p class="text-slate-600 mb-4">Premium safari tours guided by experienced rangers and naturalists.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Sunrise Safaris</h3>
            <p class="text-slate-600 mb-4">Early morning wildlife viewing with breathtaking dawn scenery.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">River Cruises</h3>
            <p class="text-slate-600 mb-4">Scenic cruises along the Kagera River with premium hospitality.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
        </div>
      </div>

      <div class="bg-slate-50 rounded-3xl p-12">
        <h2 class="text-3xl font-bold text-slate-900 mb-8 text-center">Practical Information</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Best Time to Visit</p>
            <p class="text-lg font-bold text-emerald-600">June–September</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Park Size</p>
            <p class="text-lg font-bold text-emerald-600">1,122 km²</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Temperature</p>
            <p class="text-lg font-bold text-emerald-600">22–30°C</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-emerald-600">~140 km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>