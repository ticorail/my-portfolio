<template>
  <footer class="bg-gray-800 border-t border-gray-700 py-8 mt-12">
    <div class="max-w-4xl mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
        <div>
          <h3 class="font-bold mb-4">Navigation</h3>
          <nav class="space-y-2">
            <RouterLink to="/" class="block text-gray-300 hover:text-white">Accueil</RouterLink>
            <RouterLink to="/projects" class="block text-gray-300 hover:text-white">Projets</RouterLink>
            <RouterLink to="/about" class="block text-gray-300 hover:text-white">À propos</RouterLink>
            <RouterLink to="/contact" class="block text-gray-300 hover:text-white">Contact</RouterLink>
          </nav>
        </div>

        <div>
          <h3 class="font-bold mb-4">Réseaux</h3>
          <div class="space-y-2">
            <a href="https://github.com/ticorail" class="block text-gray-300 hover:text-white">GitHub</a>
            <a href="#" class="block text-gray-300 hover:text-white">LinkedIn</a>
            <a href="#" class="block text-gray-300 hover:text-white">Twitter</a>
          </div>
        </div>

        <div>
          <h3 class="font-bold mb-4">Contact</h3>
          <p class="text-gray-300 text-sm mb-2">davidson@example.com</p>
          <p class="text-gray-300 text-sm">+33 1 23 45 67 89</p>
        </div>
      </div>

      <div class="border-t border-gray-700 pt-8 text-center text-gray-400">
        <p>&copy; 2024 Davidson. Tous droits réservés.</p>
        <p class="text-sm mt-2">Créé avec Vue.js, TypeScript et Tailwind CSS</p>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
