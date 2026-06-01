<script setup>
import northernImg from '../../assets/volcano.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Northern Rwanda</h1>
          <p class="text-xl text-slate-600 leading-relaxed mb-6">Home to Volcanoes National Park and mountain gorillas, Northern Rwanda delivers unforgettable nature and adventure experiences.</p>
          <div class="space-y-6">
            <div>
              <h3 class="font-bold text-slate-900">Volcanoes National Park</h3>
              <p class="text-slate-600 text-sm">Premium gorilla trekking and volcanic landscapes.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Pristine Forests</h3>
              <p class="text-slate-600 text-sm">Rich biodiversity and endemic mountain wildlife.</p>
            </div>
            <div>
              <h3 class="font-bold text-slate-900">Mountain Climate</h3>
              <p class="text-slate-600 text-sm">Cool air, misty hills, and dramatic scenic views.</p>
            </div>
          </div>
        </div>
        <div class="relative rounded-[32px] h-96 overflow-hidden shadow-lg">
          <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${northernImg})` }"></div>
          <div class="absolute inset-0 bg-slate-950/35"></div>
          <div class="relative z-10 flex h-full items-center justify-center text-white text-center px-8">
            <div>
              <p class="text-2xl font-semibold">Northern Rwanda</p>
              <p class="mt-4 text-sm text-slate-100">A destination for premium nature travel and conservation-led experiences.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="mb-16">
        <h2 class="text-4xl font-bold text-slate-900 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Gorilla Trekking</h3>
            <p class="text-slate-600 mb-4">Encounter mountain gorillas in their protected habitat with expert guides and sustainable permits.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Hiking Trails</h3>
            <p class="text-slate-600 mb-4">Explore volcano routes and mountain trails with panoramic views of the landscape.</p>
            <button class="text-emerald-600 font-semibold hover:text-emerald-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-3xl p-8 shadow-md hover:shadow-xl transition">
            <h3 class="text-2xl font-bold text-slate-900 mb-3">Photography Tours</h3>
            <p class="text-slate-600 mb-4">Capture dramatic wildlife and mountain vistas with support from experienced local photographers.</p>
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
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Altitude</p>
            <p class="text-lg font-bold text-emerald-600">2,400–4,507m</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Temperature</p>
            <p class="text-lg font-bold text-emerald-600">10–20°C</p>
          </div>
          <div>
            <p class="text-sm text-slate-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-emerald-600">~100 km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>