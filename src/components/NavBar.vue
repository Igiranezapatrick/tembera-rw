<script setup>
import { ref, onMounted, onUnmounted } from 'vue'
import { RouterLink } from 'vue-router'

// Track which dropdown is currently active (null if none)
const activeDropdown = ref(null)

// Toggle specific dropdown and close others
const toggleDropdown = (dropdownName) => {
  if (activeDropdown.value === dropdownName) {
    activeDropdown.value = null
  } else {
    activeDropdown.value = dropdownName
  }
}

// Close dropdown when clicking outside
const onClickOutside = (event) => {
  if (!event.target.closest('.nav-dropdown')) {
    activeDropdown.value = null
  }
}

onMounted(() => {
  document.addEventListener('click', onClickOutside)
})

onUnmounted(() => {
  document.removeEventListener('click', onClickOutside)
})
</script>

<template>
  <nav class="sticky top-0 z-50 bg-white/95 border-b border-slate-200 px-8 py-4 backdrop-blur-sm">
    <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-6">
      <div class="flex items-center gap-4 flex-shrink-0">
        <div class="grid h-11 w-11 place-items-center rounded-2xl bg-emerald-700 text-white text-lg font-semibold tracking-[0.24em] shadow-sm">TR</div>
        <div>
          <div class="text-lg font-semibold tracking-[0.18em] uppercase text-slate-900">Tembera Urwanda</div>
          <div class="text-xs text-slate-500 uppercase tracking-[0.28em]">Rwanda Travel</div>
        </div>
      </div>

      <ul class="flex flex-wrap items-center gap-6 md:gap-8 list-none p-0 m-0 text-sm text-slate-700">
        <li class="hover:text-emerald-700 transition duration-300">
          <RouterLink to="/" class="font-medium">Home</RouterLink>
        </li>
        <li class="hover:text-emerald-700 transition duration-300">
          <RouterLink to="/about" class="font-medium">About</RouterLink>
        </li>
        <li class="hover:text-emerald-700 transition duration-300">
          <RouterLink to="/services" class="font-medium">Services</RouterLink>
        </li>

        <li class="nav-dropdown relative cursor-pointer py-2">
          <span
            @click="toggleDropdown('gallery')"
            class="hover:text-emerald-700 flex items-center gap-2 select-none font-medium transition duration-300"
          >
            Gallery
            <span class="text-xs transition-transform duration-300" :class="{ 'rotate-180': activeDropdown === 'gallery' }">
              ▾
            </span>
          </span>
          <ul v-if="activeDropdown === 'gallery'" class="absolute left-0 top-full mt-2 bg-white text-slate-900 rounded-2xl shadow-xl py-3 w-52 z-50 border border-slate-200">
            <li class="hover:bg-slate-50">
              <RouterLink to="/gallery/photos" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Photos</RouterLink>
            </li>
            <li class="hover:bg-slate-50 border-t border-slate-200">
              <RouterLink to="/gallery/videos" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Videos</RouterLink>
            </li>
          </ul>
        </li>

        <li class="nav-dropdown relative cursor-pointer py-2">
          <span
            @click="toggleDropdown('destinations')"
            class="hover:text-emerald-700 flex items-center gap-2 select-none font-medium transition duration-300"
          >
            Destinations
            <span class="text-xs transition-transform duration-300" :class="{ 'rotate-180': activeDropdown === 'destinations' }">
              ▾
            </span>
          </span>
          <ul v-if="activeDropdown === 'destinations'" class="absolute left-0 top-full mt-2 bg-white text-slate-900 rounded-2xl shadow-xl py-3 w-52 z-50 border border-slate-200">
            <li class="hover:bg-slate-50">
              <RouterLink to="/dest/northern" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Northern</RouterLink>
            </li>
            <li class="hover:bg-slate-50 border-t border-slate-200">
              <RouterLink to="/dest/southern" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Southern</RouterLink>
            </li>
            <li class="hover:bg-slate-50 border-t border-slate-200">
              <RouterLink to="/dest/eastern" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Eastern</RouterLink>
            </li>
            <li class="hover:bg-slate-50 border-t border-slate-200">
              <RouterLink to="/dest/western" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Western</RouterLink>
            </li>
            <li class="hover:bg-slate-50 border-t border-slate-200">
              <RouterLink to="/dest/kigali" class="block px-4 py-3 hover:text-emerald-700 font-medium transition">Kigali</RouterLink>
            </li>
          </ul>
        </li>

        <li class="hover:text-emerald-700 transition duration-300">
          <RouterLink to="/contacts" class="font-medium">Contact</RouterLink>
        </li>
      </ul>
    </div>
  </nav>

</template>
