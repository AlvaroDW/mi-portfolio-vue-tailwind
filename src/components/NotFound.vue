<template>
  <div class="min-h-screen flex flex-col items-center justify-center bg-gray-100 text-center px-6">
    <h1 class="text-6xl font-extrabold text-indigo-600 mb-4">404</h1>
    <h2 class="text-2xl font-semibold text-gray-800 mb-2">Página no encontrada</h2>
    <p class="text-gray-600 mb-6">
      Lo sentimos, la página que buscas no existe o ha sido movida.
    </p>
    <router-link
      to="/"
      class="bg-indigo-600 text-white px-6 py-3 rounded-lg font-medium hover:bg-indigo-700 transition"
    >
      Volver al inicio
    </router-link>
  </div>
</template>
