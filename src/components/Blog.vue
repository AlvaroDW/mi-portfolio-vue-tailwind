<template>
  <section id="blog" class="bg-white py-16 px-6 md:px-12">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold mb-10 text-center text-gray-800">Blog</h2>
      <div class="grid gap-8 md:grid-cols-2">
        <article
          v-for="post in posts"
          :key="post.titulo"
          class="bg-gray-50 border border-gray-200 rounded-lg p-6 shadow-sm hover:shadow-lg transition"
        >
          <h3 class="text-xl font-semibold mb-2 text-blue-700">{{ post.titulo }}</h3>
          <p class="text-gray-500 text-sm mb-4">📅 {{ post.fecha }}</p>
          <p class="text-gray-700 leading-relaxed">{{ post.descripcion }}</p>
        </article>
      </div>
    </div>
  </section>
</template>

<script setup>
const posts = [
  {
    titulo: 'Protege tu aplicación web: buenas prácticas de seguridad',
    fecha: '18 de mayo de 2025',
    descripcion:
      'Una guía rápida sobre cómo aplicar medidas de seguridad básicas en tus desarrollos web usando cabeceras HTTP, validación de entradas y más.'
  },
  {
    titulo: 'Integración de Tailwind CSS en proyectos Vue 3 con Vite',
    fecha: '12 de mayo de 2025',
    descripcion:
      'Paso a paso para usar Tailwind CSS con Vue y Vite para lograr interfaces modernas y mantenibles.'
  }
]
</script>

<style scoped>
/* Puedes agregar animaciones o estilos personalizados si lo deseas */
</style>
