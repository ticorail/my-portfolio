<template>
  <section class="min-h-screen py-12">
    <div class="max-w-4xl mx-auto px-4">
      <h1 class="text-center mb-12">Mes Projets</h1>
      
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="card">
          <h3 class="text-2xl font-bold mb-3">Portfolio Personnel</h3>
          <p class="text-gray-300 mb-4">
            Un portfolio interactif construit avec Vue.js, TypeScript et Tailwind CSS.
          </p>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-blue-600 rounded-full text-sm">Vue.js</span>
            <span class="px-3 py-1 bg-blue-600 rounded-full text-sm">TypeScript</span>
            <span class="px-3 py-1 bg-blue-600 rounded-full text-sm">Tailwind</span>
          </div>
        </div>

        <div class="card">
          <h3 class="text-2xl font-bold mb-3">Application e-Commerce</h3>
          <p class="text-gray-300 mb-4">
            Plateforme complète avec catalogue de produits et système de paiement.
          </p>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-green-600 rounded-full text-sm">Node.js</span>
            <span class="px-3 py-1 bg-green-600 rounded-full text-sm">Express</span>
            <span class="px-3 py-1 bg-green-600 rounded-full text-sm">MongoDB</span>
          </div>
        </div>

        <div class="card">
          <h3 class="text-2xl font-bold mb-3">Task Manager</h3>
          <p class="text-gray-300 mb-4">
            Application de gestion de tâches avec authentification et base de données.
          </p>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-purple-600 rounded-full text-sm">Vue.js</span>
            <span class="px-3 py-1 bg-purple-600 rounded-full text-sm">Firebase</span>
            <span class="px-3 py-1 bg-purple-600 rounded-full text-sm">Responsive</span>
          </div>
        </div>

        <div class="card">
          <h3 class="text-2xl font-bold mb-3">API REST</h3>
          <p class="text-gray-300 mb-4">
            API robuste avec authentification JWT et documentation Swagger complète.
          </p>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-orange-600 rounded-full text-sm">Node.js</span>
            <span class="px-3 py-1 bg-orange-600 rounded-full text-sm">JWT</span>
            <span class="px-3 py-1 bg-orange-600 rounded-full text-sm">REST</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
