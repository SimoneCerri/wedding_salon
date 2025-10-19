<template>
    <footer class="bg-st-dark text-dark py-4">
        <div class="container text-center">
            <p class="mb-2">Spoiler, Ti Sposo! | Since 2025</p>
            <p class="mb-0">
                <small>&copy; {{ currentYear }} Tutti i Diritti Riservati a ScorpioN 🖤</small>
            </p>
            <div class="mt-2">
                <a href="#home" class="text-white mx-2 text-decoration-none hover-link">Home</a>
                <a href="#services" class="text-white mx-2 text-decoration-none hover-link">Servizi</a>
                <a href="#gallery" class="text-white mx-2 text-decoration-none hover-link">Galleria</a>
                <a href="#contact" class="text-white mx-2 text-decoration-none hover-link">Contatti</a>
            </div>
        </div>
    </footer>
</template>

<script setup>
const currentYear = new Date().getFullYear();
</script>

<style scoped>
.hover-link:hover {
    color: var(--st-accent) !important;
    /* Bright red/coral color on hover */
    transition: color 0.3s;
}
</style>
