<template>
  <section class="min-h-screen py-12">
    <div class="max-w-4xl mx-auto px-4">
      <h1 class="text-center mb-8">Accueil</h1>
      <div class="text-center mb-12">
        <p class="text-xl text-gray-300 mb-6">Bienvenue sur mon portfolio</p>
        <p class="text-lg text-gray-400 mb-8">
          Je suis un développeur passionné par la création d'applications web modernes et performantes.
        </p>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-12">
        <div class="card">
          <h3 class="text-xl font-bold mb-2">Frontend</h3>
          <p class="text-gray-300">Vue.js, TypeScript, Tailwind CSS</p>
        </div>
        <div class="card">
          <h3 class="text-xl font-bold mb-2">Backend</h3>
          <p class="text-gray-300">Node.js, Express, API REST</p>
        </div>
        <div class="card">
          <h3 class="text-xl font-bold mb-2">Tools</h3>
          <p class="text-gray-300">Git, Vite, Docker</p>
        </div>
      </div>

      <div class="text-center">
        <RouterLink to="/projects" class="btn inline-block">Voir mes projets</RouterLink>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
