<template>
  <div>
    <Navbar />
    <main class="pt-20"> <!-- deja espacio para la navbar fija -->
      <Inicio />
      <SobreMi />
      <Proyectos />
      <Blog />
      <Contacto />
    </main>
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Inicio from './components/Inicio.vue'
import SobreMi from './components/SobreMi.vue'
import Proyectos from './components/Proyectos.vue'
import Blog from './components/Blog.vue'
import Contacto from './components/Contacto.vue'
</script>
<style>
body {
  font-family: system-ui, sans-serif;
}
</style>