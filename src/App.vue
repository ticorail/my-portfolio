<template>
  <div class="flex flex-col min-h-screen bg-gray-900 text-white">
    <nav class="bg-gray-800 border-b border-gray-700 sticky top-0 z-50">
      <div class="max-w-4xl mx-auto px-4 py-4 flex justify-between items-center">
        <RouterLink to="/" class="text-2xl font-bold text-blue-400 hover:text-blue-300">
          Davidson
        </RouterLink>
        <div class="flex gap-2">
          <RouterLink to="/" class="nav-link">Accueil</RouterLink>
          <RouterLink to="/projects" class="nav-link">Projets</RouterLink>
          <RouterLink to="/about" class="nav-link">À propos</RouterLink>
          <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
        </div>
      </div>
    </nav>

    <main class="flex-1">
      <RouterView />
    </main>

    <Footer />
  </div>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Footer from './components/Footer.vue'
</script>
