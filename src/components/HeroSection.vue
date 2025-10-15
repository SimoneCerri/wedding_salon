<template>
  <header id="home" class="hero-section d-flex align-items-center text-white text-center"
    style="min-height: 100vh; background-size: cover; background-position: center; position: relative; background-color:antiquewhite;">
    <div class="overlay position-absolute top-0 start-0 w-100 h-100" style="background-color: rgba(0, 0, 0, 0.45);">
    </div>
    <div class="container position-relative z-1 p-5">
      <p class="h5 mb-3 text-uppercase fw-light letter-spacing-2">Where dreams are woven into reality</p>
      <h1 class="display-1 fw-bold mb-4 animate-fade-in">The Turin Wedding Salon</h1>
      <p class="lead mb-5 fs-4">Your journey to forever begins with us. We handle every detail so you can focus on the
        magic.</p>
      <a href="#contact" class="btn btn-lg btn-light text-dark fw-bold px-5 py-3 shadow-lg rounded-pill hover-grow">
        Book a Consultation
      </a>
    </div>
  </header>
</template>

<script setup>
// No script logic needed for this static component
</script>

<style scoped>
/* Scoped custom CSS for the Hero */
.letter-spacing-2 {
  letter-spacing: 2px;
}

.animate-fade-in {
  animation: fadeIn 2s ease-out;
}

.hover-grow:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
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
