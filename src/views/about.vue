<script setup>
import aboutImg from '../assets/culture.jpg'
import gorillaThumb from '../assets/gorilla.jpg'
import parkThumb from '../assets/park.jpg'
import lakeThumb from '../assets/lake.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">About Rwanda</h1>
        <p class="text-xl text-slate-600 max-w-2xl mx-auto">Discover the heart of East Africa—an exceptional destination defined by resilience, natural beauty, and sophisticated hospitality.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <div class="relative rounded-3xl h-80 overflow-hidden shadow-xl">
            <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${aboutImg})` }"></div>
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center text-3xl text-white font-semibold">Rwanda</div>
          </div>
        </div>
        <div>
          <h2 class="text-3xl font-bold text-slate-900 mb-6">The Land of a Thousand Hills</h2>
          <p class="text-slate-700 mb-4 leading-relaxed">Rwanda, located in the heart of East Africa, is a country known for its stunning landscapes, rich biodiversity, and resilient people. Despite its small size, Rwanda offers world-class attractions and unforgettable experiences.</p>
          <p class="text-slate-700 mb-4 leading-relaxed">From the misty mountains of Volcanoes National Park to the expansive savannas of Akagera and the ancient rainforests of Nyungwe, Rwanda delivers destination diversity with exceptional service.</p>
          <p class="text-slate-700 leading-relaxed">Our commitment to sustainable tourism ensures these natural wonders are preserved for future generations while welcoming travelers from around the world.</p>
        </div>
      </div>

      <div class="bg-slate-50 rounded-3xl p-12 mb-16 shadow-lg">
        <h2 class="text-3xl font-bold text-slate-900 mb-8 text-center">Key Facts About Rwanda</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
          <div class="text-center">
            <div class="text-4xl font-bold text-emerald-700 mb-2">26,338</div>
            <p class="text-slate-600">Square kilometers</p>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-emerald-700 mb-2">13M</div>
            <p class="text-slate-600">Population</p>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-emerald-700 mb-2">23°C</div>
            <p class="text-slate-600">Average temperature</p>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-emerald-700 mb-2">29</div>
            <p class="text-slate-600">Languages spoken</p>
          </div>
        </div>
      </div>

      <div>
        <h2 class="text-3xl font-bold text-slate-900 mb-8 text-center">Why Rwanda Stands Out</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white p-8 rounded-3xl shadow-md hover:shadow-xl transition">
            <div class="h-12 w-12 mb-4 rounded-3xl bg-cover bg-center" :style="{ backgroundImage: `url(${gorillaThumb})` }"></div>
            <h3 class="text-xl font-bold text-slate-900 mb-3">Incredible Wildlife</h3>
            <p class="text-slate-600">World-class wildlife experiences in protected national parks and conservation areas.</p>
          </div>
          <div class="bg-white p-8 rounded-3xl shadow-md hover:shadow-xl transition">
            <div class="h-12 w-12 mb-4 rounded-3xl bg-cover bg-center" :style="{ backgroundImage: `url(${parkThumb})` }"></div>
            <h3 class="text-xl font-bold text-slate-900 mb-3">Breathtaking Scenery</h3>
            <p class="text-slate-600">Rolling hills, volcanic peaks, and pristine lakes define Rwanda’s elegant landscapes.</p>
          </div>
          <div class="bg-white p-8 rounded-3xl shadow-md hover:shadow-xl transition">
            <div class="h-12 w-12 mb-4 rounded-3xl bg-cover bg-center" :style="{ backgroundImage: `url(${lakeThumb})` }"></div>
            <h3 class="text-xl font-bold text-slate-900 mb-3">Authentic Culture</h3>
            <p class="text-slate-600">Rich cultural experiences delivered with warmth, respect, and local insight.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>