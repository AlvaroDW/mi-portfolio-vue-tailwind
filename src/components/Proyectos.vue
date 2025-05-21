<template>
  <section id="proyectos" class="bg-gray-50 py-12 px-6 md:px-12">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">Proyectos</h2>
      <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
        <div v-for="proyecto in proyectos" :key="proyecto.id" class="bg-white rounded-lg shadow-md p-6 hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">{{ proyecto.titulo }}</h3>
          <p class="text-gray-700 mb-4">{{ proyecto.descripcion }}</p>
          <a :href="proyecto.enlace" target="_blank" class="text-blue-600 hover:underline">Ver proyecto</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const proyectos = [
  {
    id: 1,
    titulo: 'Gestor de Tareas en PHP',
    descripcion: 'Aplicación CRUD usando PHP y MySQL con arquitectura MVC.',
    enlace: '#'
  },
  {
    id: 2,
    titulo: 'Escáner de Vulnerabilidades en Python',
    descripcion: 'Herramienta CLI para detectar vulnerabilidades básicas en servidores web.',
    enlace: '#'
  },
  {
    id: 3,
    titulo: 'Portfolio en Vue',
    descripcion: 'Este mismo sitio, construido con Vue.js y Tailwind CSS.',
    enlace: '#'
  }
]
</script>

<style scoped>
/* Puedes personalizar los estilos si lo deseas */
</style>
