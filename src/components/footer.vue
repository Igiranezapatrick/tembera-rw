<template>
  <footer class="bg-slate-900 text-slate-100 px-8 py-16 mt-16 shadow-2xl">
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-left mb-12 max-w-7xl mx-auto">
      <div class="flex flex-col justify-center items-center lg:items-start text-center lg:text-left">
        <h3 class="text-4xl font-extrabold tracking-tight text-white mb-2 leading-tight">
          TEMBERA URWANDA
        </h3>
        <p class="text-sm text-slate-300 mb-4">Professional Rwanda travel and hospitality services</p>
        <div class="flex flex-wrap gap-4 justify-center lg:justify-start text-sm">
          <a href="#" class="text-slate-300 hover:text-white transition">Facebook</a>
          <a href="#" class="text-slate-300 hover:text-white transition">Twitter</a>
          <a href="#" class="text-slate-300 hover:text-white transition">LinkedIn</a>
        </div>
      </div>

      <div>
        <h4 class="font-bold text-lg mb-6 uppercase tracking-wider border-b border-slate-700 pb-3">Quick Links</h4>
        <ul class="space-y-3 text-sm text-slate-300">
          <li><router-link to="/" class="hover:text-white transition duration-300 font-medium">Home</router-link></li>
          <li><router-link to="/about" class="hover:text-white transition duration-300 font-medium">About Rwanda</router-link></li>
          <li><router-link to="/services" class="hover:text-white transition duration-300 font-medium">Services</router-link></li>
          <li><router-link to="/contacts" class="hover:text-white transition duration-300 font-medium">Contact</router-link></li>
        </ul>
      </div>

      <div>
        <h4 class="font-bold text-lg mb-6 uppercase tracking-wider border-b border-slate-700 pb-3">Top Destinations</h4>
        <ul class="space-y-3 text-sm text-slate-300">
          <li><a href="#" class="hover:text-white transition duration-300 font-medium">Volcanoes National Park</a></li>
          <li><a href="#" class="hover:text-white transition duration-300 font-medium">Nyungwe National Park</a></li>
          <li><a href="#" class="hover:text-white transition duration-300 font-medium">Akagera National Park</a></li>
          <li><a href="#" class="hover:text-white transition duration-300 font-medium">Lake Kivu</a></li>
        </ul>
      </div>

      <div>
        <h4 class="font-bold text-lg mb-6 uppercase tracking-wider border-b border-slate-700 pb-3">Contact Info</h4>
        <ul class="space-y-3 text-sm text-slate-300">
          <li>Gacuriro, Kigali, Rwanda</li>
          <li>info@temberaurwanda.com</li>
          <li>+250 123 456 789</li>
          <li>24/7 Support</li>
        </ul>
      </div>
    </div>

    <div class="border-t border-slate-700 my-8 max-w-7xl mx-auto"></div>

    <div class="max-w-7xl mx-auto">
      <div class="flex flex-col md:flex-row justify-between items-center text-center md:text-left gap-6 text-sm text-slate-400">
        <p>Created by Igiraneza Patrick</p>
        <div class="flex flex-wrap gap-6 justify-center md:justify-end">
          <a href="#" class="hover:text-white transition">Privacy Policy</a>
          <a href="#" class="hover:text-white transition">Terms & Conditions</a>
          <a href="#" class="hover:text-white transition">Sitemap</a>
        </div>
      </div>
    </div>
  </footer>
</template>
