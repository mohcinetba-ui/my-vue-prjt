<script setup>
const projets = [
    "portfolio Vue.js",
    "Gestion Bibliotheque",
    "Application Generateur CV PDF"
]
</script>
 
<template>
    <section>
        <h2>Mes projets</h2>
        <ul>
            <li 
              v-for="projet in projets"
               :key="projet"
               >
               {{ projet }}
            </li>
        </ul>
    </section>
</template>