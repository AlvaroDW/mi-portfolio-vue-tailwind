<template>
  <section id="contacto" class="py-16 bg-gray-100 px-6 md:px-12">
    <div class="max-w-3xl mx-auto bg-white p-8 rounded-xl shadow-md">
      <h2 class="text-3xl font-bold mb-6 text-center">Contacto</h2>
      <form class="space-y-6">
        <div>
          <label for="nombre" class="block mb-2 font-medium">Nombre</label>
          <input
            id="nombre"
            type="text"
            placeholder="Tu nombre"
            class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500"
          />
        </div>
        <div>
          <label for="email" class="block mb-2 font-medium">Email</label>
          <input
            id="email"
            type="email"
            placeholder="tucorreo@example.com"
            class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500"
          />
        </div>
        <div>
          <label for="mensaje" class="block mb-2 font-medium">Mensaje</label>
          <textarea
            id="mensaje"
            rows="5"
            placeholder="Escribe tu mensaje"
            class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-500"
          ></textarea>
        </div>
        <button
          type="submit"
          class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition"
        >
          Enviar mensaje
        </button>
      </form>
    </div>
  </section>
</template>

<script setup>
// Lógica de envío se agregará más adelante
</script>

<style scoped>
/* Puedes personalizar más si lo deseas */
</style>
