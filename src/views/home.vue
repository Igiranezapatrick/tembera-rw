<script setup>
import gorillaBg from '../assets/gorilla2.jpg'
import heroImg from '../assets/hero.png'
import parkImg from '../assets/park.jpg'
import cultureImg from '../assets/culture.jpg'
</script>
<template>
  <section class="min-h-screen bg-slate-50">
    <div class="relative overflow-hidden">
      <div class="absolute inset-0 bg-slate-950/45"></div>
      <div class="relative min-h-[78vh] flex items-center justify-center">
        <div class="absolute inset-0 bg-cover bg-center" :style="{ backgroundImage: `url(${gorillaBg})` }"></div>
        <div class="absolute inset-0 bg-gradient-to-b from-slate-950/10 via-slate-950/10 to-slate-950/90"></div>
        <div class="relative z-10 px-6 py-24 text-center">
          <p class="mb-4 text-sm uppercase tracking-[0.35em] text-emerald-300">Rwanda Travel & Hospitality</p>
          <h1 class="text-5xl md:text-6xl font-extrabold tracking-tight text-white leading-tight">Tembera Urwanda</h1>
          <p class="mt-6 text-lg md:text-xl text-slate-200 max-w-3xl mx-auto leading-relaxed">Executive travel services for Rwanda's premier destinations, cultural experiences, and bespoke safari journeys.</p>
          <div class="mt-10 flex flex-col items-center justify-center gap-4 sm:flex-row">
            <button class="px-10 py-4 rounded-full bg-emerald-600 text-white font-semibold tracking-wide hover:bg-emerald-700 transition shadow-xl">Discover Rwanda</button>
            <button class="px-10 py-4 rounded-full border border-white/20 bg-white/10 text-white font-semibold tracking-wide hover:bg-white/20 transition">View Services</button>
          </div>
        </div>
      </div>
    </div>

    <section class="py-20">
      <div class="max-w-7xl mx-auto px-4">
        <div class="grid gap-12 lg:grid-cols-3">
          <div class="group overflow-hidden rounded-[32px] shadow-xl bg-white">
            <div class="h-48 bg-cover bg-center" :style="{ backgroundImage: `url(${heroImg})` }"></div>
            <div class="p-10">
              <span class="inline-flex h-12 w-12 items-center justify-center rounded-3xl bg-emerald-100 text-emerald-700 font-semibold">01</span>
              <h2 class="mt-8 text-2xl font-bold text-slate-900">Premium Experiences</h2>
              <p class="mt-4 text-slate-600 leading-relaxed">Curated itineraries and seamless travel planning for guests seeking the best of Rwanda.</p>
            </div>
          </div>
          <div class="group overflow-hidden rounded-[32px] shadow-xl bg-white">
            <div class="h-48 bg-cover bg-center" :style="{ backgroundImage: `url(${parkImg})` }"></div>
            <div class="p-10">
              <span class="inline-flex h-12 w-12 items-center justify-center rounded-3xl bg-emerald-100 text-emerald-700 font-semibold">02</span>
              <h2 class="mt-8 text-2xl font-bold text-slate-900">Trusted Local Expertise</h2>
              <p class="mt-4 text-slate-600 leading-relaxed">Professional guides, premium accommodations, and sustainable travel support across every region.</p>
            </div>
          </div>
          <div class="group overflow-hidden rounded-[32px] shadow-xl bg-white">
            <div class="h-48 bg-cover bg-center" :style="{ backgroundImage: `url(${cultureImg})` }"></div>
            <div class="p-10">
              <span class="inline-flex h-12 w-12 items-center justify-center rounded-3xl bg-emerald-100 text-emerald-700 font-semibold">03</span>
              <h2 class="mt-8 text-2xl font-bold text-slate-900">Seamless Service</h2>
              <p class="mt-4 text-slate-600 leading-relaxed">From airport arrival to bespoke excursions, we ensure every moment is expertly coordinated.</p>
            </div>
          </div>
        </div>

        <div class="mt-20 rounded-[32px] bg-slate-950 text-white p-12 shadow-2xl">
          <div class="grid gap-8 lg:grid-cols-3">
            <div>
              <h3 class="text-lg uppercase tracking-[0.25em] text-emerald-300">Trusted Partners</h3>
              <p class="mt-4 text-slate-300 leading-relaxed">We collaborate with top lodges, transport providers, and local experts to deliver consistent service.</p>
            </div>
            <div>
              <h3 class="text-lg uppercase tracking-[0.25em] text-emerald-300">Luxury Accommodations</h3>
              <p class="mt-4 text-slate-300 leading-relaxed">Exclusive stays in Rwanda's most prestigious lodges, hotels, and safari camps.</p>
            </div>
            <div>
              <h3 class="text-lg uppercase tracking-[0.25em] text-emerald-300">Heritage & Culture</h3>
              <p class="mt-4 text-slate-300 leading-relaxed">Authentic cultural experiences that connect travelers with Rwanda's people and history.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>