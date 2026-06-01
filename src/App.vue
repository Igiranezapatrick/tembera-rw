<script setup>
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
import Footer from './components/footer.vue'
</script>

<template>
  <div class="min-h-screen flex flex-col bg-white">
    <NavBar />
    <main class="flex-grow bg-slate-50">
      <RouterView />
    </main>
    <Footer />
  </div>
</template>
