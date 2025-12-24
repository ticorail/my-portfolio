<template>
  <section class="min-h-screen py-12">
    <div class="max-w-2xl mx-auto px-4">
      <h1 class="text-center mb-12">Contactez-moi</h1>
      
      <div class="card mb-12">
        <p class="text-gray-300 mb-8">
          N'hésitez pas à me contacter pour discuter de vos projets ou si vous avez des questions. 
          Je serai ravi de collaborer avec vous!
        </p>

        <div class="space-y-6">
          <div class="flex items-start gap-4">
            <span class="text-blue-400 text-2xl">📧</span>
            <div>
              <h3 class="font-bold mb-1">Email</h3>
              <a href="mailto:davidson@example.com" class="text-blue-400 hover:text-blue-300">
                davidson@example.com
              </a>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <span class="text-blue-400 text-2xl">💼</span>
            <div>
              <h3 class="font-bold mb-1">LinkedIn</h3>
              <a href="#" class="text-blue-400 hover:text-blue-300">
                linkedin.com/in/davidson
              </a>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <span class="text-blue-400 text-2xl">🐙</span>
            <div>
              <h3 class="font-bold mb-1">GitHub</h3>
              <a href="https://github.com/ticorail" class="text-blue-400 hover:text-blue-300">
                github.com/ticorail
              </a>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <span class="text-blue-400 text-2xl">📱</span>
            <div>
              <h3 class="font-bold mb-1">Téléphone</h3>
              <a href="tel:+33123456789" class="text-blue-400 hover:text-blue-300">
                +33 1 23 45 67 89
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="card">
        <h2 class="mb-6">Formulaire de contact</h2>
        <form class="space-y-4" @submit.prevent="handleSubmit">
          <div>
            <label class="block mb-2 font-semibold">Nom</label>
            <input 
              v-model="form.name" 
              type="text" 
              class="w-full bg-gray-700 text-white px-4 py-2 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-400"
              required
            />
          </div>

          <div>
            <label class="block mb-2 font-semibold">Email</label>
            <input 
              v-model="form.email" 
              type="email" 
              class="w-full bg-gray-700 text-white px-4 py-2 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-400"
              required
            />
          </div>

          <div>
            <label class="block mb-2 font-semibold">Message</label>
            <textarea 
              v-model="form.message" 
              rows="5"
              class="w-full bg-gray-700 text-white px-4 py-2 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-400 resize-none"
              required
            ></textarea>
          </div>

          <button type="submit" class="btn w-full">Envoyer le message</button>
        </form>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const form = ref({
  name: '',
  email: '',
  message: ''
})

const handleSubmit = () => {
  console.log('Message envoyé:', form.value)
  alert('Merci pour votre message!')
  form.value = { name: '', email: '', message: '' }
}
</script>
