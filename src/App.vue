<template>
  <nav class="p-4 border-b flex gap-6">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/projects">Projects</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/contact">Contact</RouterLink>
  </nav>

  <main class="p-6">
    <RouterView />
  </main>
</template>
