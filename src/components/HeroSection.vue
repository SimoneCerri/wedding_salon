<template>
  <header id="home"
    class="hero-section d-flex flex-column align-items-center justify-content-center text-white text-center"
    style="min-height: 100vh; background-size: cover; background-position: center; position: relative; background-image: url(/sfondo_hero.jpg);">
    <div class="overlay position-absolute top-0 start-0 w-100 h-100" style="background-color: rgba(0, 0, 0, 0.45);">
    </div>
    <div class="container position-relative z-1 p-5">

      <!-- Logo Integration -->
      <img src="/logo_quadrato_no_bg.png" alt="Spoiler, Ti Sposo! Logo" class="mb-4 logo-style" loading="lazy"
        onerror="this.onerror=null;this.src='https://placehold.co/400x100/333/fff?text=Spoiler+Ti+Sposo+Logo';">
      <p class="h5 mb-3 text-uppercase fw-light letter-spacing-2">Dove i sogni prendono forma</p>
      <h1 class="display-1 fw-bold mb-4 animate-fade-in custom-font-heading">Spoiler, Ti Sposo!</h1>
      <p class="lead mb-5 fs-4">Il vostro viaggio verso il per sempre inizia con noi. Ci occupiamo di ogni dettaglio
        affinché possiate concentrarvi sulla magia.</p>
      <a href="#contact" class="btn btn-lg btn-st-accent fw-bold px-5 py-3 shadow-lg rounded-pill hover-grow">
        Prenota una Consulenza Gratuita
      </a>
    </div>
  </header>
</template>

<script setup>
// No script logic needed for this static component
</script>

<style scoped>
/* Scoped custom CSS for the Hero */

.container {
  margin-top: -7em;
}

.logo-style {
  max-width: 700px;
  margin: 0;
  margin: -7em;
  height: auto;
  filter: drop-shadow(0 0 5px rgba(255, 255, 255, 0.5));
}

@media (max-width: 768px) {
  .logo-style {
    max-width: 550px;
  }
}

@media (max-width: 390px) {
  .logo-style {
    margin: 0;
  }
}

.letter-spacing-2 {
  letter-spacing: 2px;
}

.animate-fade-in {
  animation: fadeIn 2s ease-out;
}

.hover-grow:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease-in-out;
}

.overlay {
  border-radius: 20px 20px 0 0;
  background-image: url(/floreale.jpg);
  background-position: center;
  background-size: cover;
}

.btn {
  background-color: #fce8f27c;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
