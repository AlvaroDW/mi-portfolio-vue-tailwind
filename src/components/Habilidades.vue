<template>
  <section id="habilidades" class="bg-gray-50 py-20 px-6 md:px-12">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold text-center text-gray-800 mb-12" data-aos="fade-down">Habilidades Técnicas</h2>
      <div class="grid md:grid-cols-3 gap-10">
        <div v-for="categoria in habilidades" :key="categoria.titulo" class="bg-white rounded-xl shadow-md p-6" data-aos="zoom-in">
          <h3 class="text-xl font-semibold text-indigo-600 mb-4">{{ categoria.titulo }}</h3>
          <ul class="space-y-2 text-gray-700">
            <li v-for="item in categoria.items" :key="item" class="flex items-center gap-2">
              <span class="text-indigo-500">✔</span> {{ item }}
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const habilidades = [
  {
    titulo: "Lenguajes y Frameworks",
    items: [
      "PHP (Laravel, Slim)",
      "Python (Flask, FastAPI)",
      "JavaScript (Vue.js, Vite)",
      "HTML5, CSS3, Tailwind CSS"
    ]
  },
  {
    titulo: "DevOps y Herramientas",
    items: [
      "Git y GitHub",
      "Docker y Docker Compose",
      "Vite, Webpack",
      "Linux (CLI, administración básica)"
    ]
  },
  {
    titulo: "Ciberseguridad",
    items: [
      "OWASP Top 10",
      "Auditoría básica de aplicaciones web",
      "Hardening de servidores",
      "Uso de herramientas como Nmap, Burp Suite"
    ]
  }
]
</script>
