<script setup>
import volcanoImg from '../assets/volcano.jpg'
import parkImg from '../assets/park.jpg'
import lakeImg from '../assets/lake.jpg'
import kivuImg from '../assets/kivu.jpg'
import cityImg from '../assets/image.jpg'
import gorillaImg from '../assets/gorilla.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Explore Our Destinations</h1>
        <p class="text-xl text-slate-600 max-w-2xl mx-auto">Each destination offers refined experiences and exceptional natural beauty across Rwanda.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-48 bg-cover bg-center relative" :style="{ backgroundImage: `url(${volcanoImg})` }">
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center">
              <span class="text-lg font-semibold text-white">Volcanoes National Park</span>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-2">Volcanoes National Park</h3>
            <p class="text-slate-600 mb-4">Home to mountain gorillas and dramatic volcanic scenery in Rwanda's northern highlands.</p>
            <div class="space-y-2 mb-6 text-sm text-slate-600">
              <p><strong>Best Time:</strong> June–September, December–January</p>
              <p><strong>Altitude:</strong> 2,400–4,507m</p>
              <p><strong>Highlights:</strong> Gorilla trekking, volcanic climbs</p>
            </div>
            <button class="w-full bg-emerald-600 text-white py-2 rounded-lg font-semibold hover:bg-emerald-700 transition">Learn More</button>
          </div>
        </div>

        <div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-48 bg-cover bg-center relative" :style="{ backgroundImage: `url(${parkImg})` }">
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center">
              <span class="text-lg font-semibold text-white">Nyungwe National Park</span>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-2">Nyungwe National Park</h3>
            <p class="text-slate-600 mb-4">Ancient rainforest with diverse wildlife, canopy walkways, and premium nature experiences.</p>
            <div class="space-y-2 mb-6 text-sm text-slate-600">
              <p><strong>Best Time:</strong> Year-round</p>
              <p><strong>Area:</strong> 970 km²</p>
              <p><strong>Highlights:</strong> Canopy walks, primate tracking</p>
            </div>
            <button class="w-full bg-emerald-600 text-white py-2 rounded-lg font-semibold hover:bg-emerald-700 transition">Learn More</button>
          </div>
        </div>

        <div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-48 bg-cover bg-center relative" :style="{ backgroundImage: `url(${kivuImg})` }">
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center">
              <span class="text-lg font-semibold text-white">Akagera National Park</span>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-2">Akagera National Park</h3>
            <p class="text-slate-600 mb-4">Rwanda's premier savanna reserve, featuring diverse wildlife and luxury safari experiences.</p>
            <div class="space-y-2 mb-6 text-sm text-slate-600">
              <p><strong>Best Time:</strong> June–September</p>
              <p><strong>Area:</strong> 1,122 km²</p>
              <p><strong>Highlights:</strong> Safari, Big Five wildlife</p>
            </div>
            <button class="w-full bg-emerald-600 text-white py-2 rounded-lg font-semibold hover:bg-emerald-700 transition">Learn More</button>
          </div>
        </div>

        <div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-48 bg-cover bg-center relative" :style="{ backgroundImage: `url(${lakeImg})` }">
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center">
              <span class="text-lg font-semibold text-white">Lake Kivu</span>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-2">Lake Kivu</h3>
            <p class="text-slate-600 mb-4">A stunning freshwater lake offering premium resorts, calm waters, and lakeside relaxation.</p>
            <div class="space-y-2 mb-6 text-sm text-slate-600">
              <p><strong>Location:</strong> Western Rwanda</p>
              <p><strong>Water Temp:</strong> 23–25°C</p>
              <p><strong>Highlights:</strong> Kayaking, beaches, lakefront dining</p>
            </div>
            <button class="w-full bg-emerald-600 text-white py-2 rounded-lg font-semibold hover:bg-emerald-700 transition">Learn More</button>
          </div>
        </div>

        <div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-48 bg-cover bg-center relative" :style="{ backgroundImage: `url(${cityImg})` }">
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center">
              <span class="text-lg font-semibold text-white">Kigali City</span>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-2">Kigali City</h3>
            <p class="text-slate-600 mb-4">Rwanda's modern capital, offering cultural landmarks, dining, and polished urban experiences.</p>
            <div class="space-y-2 mb-6 text-sm text-slate-600">
              <p><strong>Population:</strong> ~1.2M</p>
              <p><strong>Altitude:</strong> 1,567m</p>
              <p><strong>Highlights:</strong> Museums, markets, business travel</p>
            </div>
            <button class="w-full bg-emerald-600 text-white py-2 rounded-lg font-semibold hover:bg-emerald-700 transition">Learn More</button>
          </div>
        </div>

        <div class="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-48 bg-cover bg-center relative" :style="{ backgroundImage: `url(${gorillaImg})` }">
            <div class="absolute inset-0 bg-slate-950/30"></div>
            <div class="relative z-10 flex h-full items-center justify-center">
              <span class="text-lg font-semibold text-white">Musanze</span>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-2">Musanze (Ruhengeri)</h3>
            <p class="text-slate-600 mb-4">Gateway to Volcanoes National Park with refined lodge stays and mountain scenery.</p>
            <div class="space-y-2 mb-6 text-sm text-slate-600">
              <p><strong>Location:</strong> Northern Rwanda</p>
              <p><strong>Altitude:</strong> 1,800m</p>
              <p><strong>Highlights:</strong> Trekking, heritage, mountain town</p>
            </div>
            <button class="w-full bg-emerald-600 text-white py-2 rounded-lg font-semibold hover:bg-emerald-700 transition">Learn More</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>