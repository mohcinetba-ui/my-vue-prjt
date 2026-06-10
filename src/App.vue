<script setup>
import Header from './components/Header.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projets.vue';
const nom ="MOHCINE TBA"
</script>

<template>
  <div class="container">
    <Header />
    <Skills />
    <h2>À propos de moi</h2>
    <p>
      Je suis passionné par le développement web et j'apprends actuellement
      Vue.js pour créer des applications modernes.
    </p>
  </div>
</template>

<style>
.container {
  max-width: 800px;
  margin: 50px auto;
  padding: 20px;
}
</style>