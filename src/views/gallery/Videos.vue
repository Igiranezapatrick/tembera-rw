<script setup>
import heroImg from '../../assets/hero.png'
import cultureImg from '../../assets/culture.jpg'
import gorillaImg from '../../assets/gorilla.jpg'
import kivuImg from '../../assets/kivu.jpg'
import lakeImg from '../../assets/lake.jpg'
import parkImg from '../../assets/park.jpg'
const thumbnails = [heroImg, cultureImg, gorillaImg, kivuImg, lakeImg, parkImg]
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Gallery - Videos</h1>
        <p class="text-xl text-slate-600 max-w-2xl mx-auto">Cinematic footage that highlights Rwanda's landscapes, culture, and premium travel experiences.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-16">
        <div v-for="(thumb, index) in thumbnails" :key="index" class="group relative overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-72 bg-cover bg-center transition duration-300" :style="{ backgroundImage: `url(${thumb})` }"></div>
          <div class="absolute inset-0 bg-black bg-opacity-30 group-hover:bg-opacity-50 transition duration-300 flex items-center justify-center">
            <button class="w-16 h-16 bg-white rounded-full flex items-center justify-center text-slate-900 font-semibold transition group-hover:scale-110">Play</button>
          </div>
          <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black to-transparent p-4">
            <p class="text-white font-semibold">Video {{ index + 1 }}</p>
            <p class="text-slate-300 text-sm">Discover Rwanda</p>
          </div>
        </div>
      </div>

      <div class="bg-white rounded-3xl shadow-lg overflow-hidden mb-16">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 p-8">
          <div class="bg-gradient-to-br from-indigo-500 to-purple-600 h-80 rounded-3xl flex items-center justify-center text-white text-center px-8">
            <div>
              <p class="text-3xl font-semibold">Featured: Journey Through Rwanda</p>
              <p class="mt-4 text-sm text-slate-100">A premium showcase of Rwanda's natural beauty and cultural experiences.</p>
            </div>
          </div>
          <div class="flex flex-col justify-center">
            <h2 class="text-3xl font-bold text-slate-900 mb-4">Featured: Journey Through Rwanda</h2>
            <p class="text-slate-600 mb-6 leading-relaxed">Experience stunning visuals, authentic local stories, and polished production that highlights Rwanda's best destinations.</p>
            <ul class="space-y-3 mb-8 text-slate-600">
              <li>Professional cinematography and premium production values</li>
              <li>4K-resolution storytelling with elegant visuals</li>
              <li>Authentic insights from local communities</li>
            </ul>
            <button class="w-full md:w-auto px-8 py-3 bg-emerald-600 text-white rounded-full font-semibold hover:bg-emerald-700 transition">Watch Now</button>
          </div>
        </div>
      </div>

      <div class="text-center bg-slate-900 rounded-3xl p-12 text-white">
        <h2 class="text-3xl font-bold mb-4">Subscribe for Updates</h2>
        <p class="text-slate-300 mb-6 max-w-2xl mx-auto">Receive notifications about new Rwanda video releases, travel guides, and exclusive visual content.</p>
        <button class="px-8 py-3 bg-emerald-600 rounded-full font-semibold hover:bg-emerald-700 transition">Subscribe Now</button>
      </div>
    </div>
  </section>
</template>