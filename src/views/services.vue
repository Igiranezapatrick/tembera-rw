<script setup>
import planningImg from '../assets/hero.png'
import accommodationImg from '../assets/lake.jpg'
import transportImg from '../assets/image.jpg'
import documentationImg from '../assets/culture.jpg'
</script>
<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-slate-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-slate-900 mb-6">Our Services</h1>
        <p class="text-xl text-slate-600 max-w-2xl mx-auto">Comprehensive travel solutions designed for premium Rwanda experiences.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-16">
        <div class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition hover:-translate-y-1">
          <div class="h-40 bg-cover bg-center relative" :style="{ backgroundImage: `url(${planningImg})` }">
            <div class="absolute inset-0 bg-slate-950/35"></div>
            <div class="relative z-10 flex h-full items-center justify-center px-8 text-center">
              <div>
                <p class="text-xl font-semibold text-white">Travel Planning</p>
                <p class="mt-2 text-sm text-slate-200">Tailored Rwanda tours and premium itineraries.</p>
              </div>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-4">Travel Planning & Tours</h3>
            <p class="text-slate-600 mb-6 leading-relaxed">Customized packages for gorilla trekking, cultural experiences, and refined safari travel.</p>
            <ul class="space-y-3 text-slate-600 text-sm">
              <li class="pl-4 border-l-2 border-emerald-600">Guided tours to all major destinations</li>
              <li class="pl-4 border-l-2 border-emerald-600">Multi-day safari packages</li>
              <li class="pl-4 border-l-2 border-emerald-600">Adventure activities and excursions</li>
            </ul>
          </div>
        </div>

        <div class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition hover:-translate-y-1">
          <div class="h-40 bg-cover bg-center relative" :style="{ backgroundImage: `url(${accommodationImg})` }">
            <div class="absolute inset-0 bg-slate-950/35"></div>
            <div class="relative z-10 flex h-full items-center justify-center px-8 text-center">
              <div>
                <p class="text-xl font-semibold text-white">Accommodations</p>
                <p class="mt-2 text-sm text-slate-200">Luxury hotels, lodges, and boutique stays.</p>
              </div>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-4">Accommodation Booking</h3>
            <p class="text-slate-600 mb-6 leading-relaxed">Expert selection of premium hotels, eco-lodges, and five-star resorts.</p>
            <ul class="space-y-3 text-slate-600 text-sm">
              <li class="pl-4 border-l-2 border-emerald-600">3–5 star hotel partnerships</li>
              <li class="pl-4 border-l-2 border-emerald-600">Eco-lodges and boutique stays</li>
              <li class="pl-4 border-l-2 border-emerald-600">Best rate guarantees</li>
            </ul>
          </div>
        </div>

        <div class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition hover:-translate-y-1">
          <div class="h-40 bg-cover bg-center relative" :style="{ backgroundImage: `url(${transportImg})` }">
            <div class="absolute inset-0 bg-slate-950/35"></div>
            <div class="relative z-10 flex h-full items-center justify-center px-8 text-center">
              <div>
                <p class="text-xl font-semibold text-white">Transportation</p>
                <p class="mt-2 text-sm text-slate-200">Secure, comfortable transfers across Rwanda.</p>
              </div>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-4">Transportation Services</h3>
            <p class="text-slate-600 mb-6 leading-relaxed">Reliable airport transfers, private vehicles, and guided travel logistics.</p>
            <ul class="space-y-3 text-slate-600 text-sm">
              <li class="pl-4 border-l-2 border-emerald-600">Airport pick-up and drop-off</li>
              <li class="pl-4 border-l-2 border-emerald-600">Private car rentals with drivers</li>
              <li class="pl-4 border-l-2 border-emerald-600">Vehicle insurance included</li>
            </ul>
          </div>
        </div>

        <div class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition hover:-translate-y-1">
          <div class="h-40 bg-cover bg-center relative" :style="{ backgroundImage: `url(${documentationImg})` }">
            <div class="absolute inset-0 bg-slate-950/35"></div>
            <div class="relative z-10 flex h-full items-center justify-center px-8 text-center">
              <div>
                <p class="text-xl font-semibold text-white">Documentation</p>
                <p class="mt-2 text-sm text-slate-200">Visa and travel documentation support.</p>
              </div>
            </div>
          </div>
          <div class="p-8">
            <h3 class="text-2xl font-bold text-slate-900 mb-4">Visa & Documentation</h3>
            <p class="text-slate-600 mb-6 leading-relaxed">Complete assistance with permits, visas, and all required travel documents.</p>
            <ul class="space-y-3 text-slate-600 text-sm">
              <li class="pl-4 border-l-2 border-emerald-600">Visa application support</li>
              <li class="pl-4 border-l-2 border-emerald-600">Entry permit assistance</li>
              <li class="pl-4 border-l-2 border-emerald-600">Travel insurance options</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="bg-gradient-to-r from-emerald-600 to-slate-900 rounded-3xl p-12 text-white text-center">
        <h2 class="text-3xl font-bold mb-4">Ready to Explore Rwanda?</h2>
        <p class="text-lg mb-8 opacity-90">Contact us today to start planning your unforgettable African experience.</p>
        <button class="px-8 py-3 bg-white text-emerald-700 rounded-full font-semibold hover:bg-slate-100 transition">Book Your Tour Now</button>
      </div>
    </div>
  </section>
</template>