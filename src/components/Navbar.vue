<template>
  <header class="fixed top-0 left-0 w-full bg-white shadow z-50">
    <nav class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">Mi Portfolio</h1>
      <ul class="hidden md:flex space-x-6 text-gray-700 font-medium">
        <li><a href="#inicio" class="hover:text-blue-600">Inicio</a></li>
        <li><a href="#sobre-mi" class="hover:text-blue-600">Sobre mí</a></li>
        <li><a href="#proyectos" class="hover:text-blue-600">Proyectos</a></li>
        <li><a href="#blog" class="hover:text-blue-600">Blog</a></li>
        <li><a href="#contacto" class="hover:text-blue-600">Contacto</a></li>
      </ul>
    </nav>
  </header>
</template>

<script setup>
// Sin lógica aún, menú simple
</script>

<style scoped>
html {
  scroll-behavior: smooth;
}
</style>
