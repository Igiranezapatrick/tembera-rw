<script setup>
import heroImg from '../../assets/hero.png'
import cultureImg from '../../assets/culture.jpg'
import gorillaImg from '../../assets/gorilla.jpg'
import kivuImg from '../../assets/kivu.jpg'
import lakeImg from '../../assets/lake.jpg'
import parkImg from '../../assets/park.jpg'
import volcanoImg from '../../assets/volcano.jpg'
import gorilla2Img from '../../assets/gorilla2.jpg'
import imageImg from '../../assets/image.jpg'
const images = [heroImg, cultureImg, gorillaImg, kivuImg, lakeImg, parkImg, volcanoImg, gorilla2Img, imageImg]
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Gallery - Photos</h1>
        <p class="text-xl text-slate-600 max-w-2xl mx-auto">Curated imagery from Rwanda's premier landscapes and experiences.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
        <div v-for="(photo, index) in images" :key="index" class="group relative overflow-hidden rounded-3xl shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="h-64 bg-cover bg-center transition duration-300" :style="{ backgroundImage: `url(${photo})` }"></div>
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-30 transition duration-300 flex items-center justify-center">
            <button class="opacity-0 group-hover:opacity-100 transition px-6 py-2 bg-white text-slate-900 rounded-full font-semibold">View</button>
          </div>
          <div class="absolute bottom-4 left-4 text-white drop-shadow-lg">
            <span class="text-base font-semibold">Photo {{ index + 1 }}</span>
          </div>
        </div>
      </div>

      <div class="text-center bg-slate-900 rounded-3xl p-12 text-white">
        <h2 class="text-3xl font-bold mb-4">Share Your Rwanda Photos</h2>
        <p class="text-slate-300 mb-6 max-w-2xl mx-auto">Submit your best travel imagery to be featured among our premium Rwanda visuals.</p>
        <button class="px-8 py-3 bg-emerald-600 rounded-full font-semibold hover:bg-emerald-700 transition">Submit Your Photos</button>
      </div>
    </div>
  </section>
</template>