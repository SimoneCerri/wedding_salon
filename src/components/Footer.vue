<template>
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p class="mb-2">The Gilded Aisle Wedding Salon | Est. 2010</p>
            <p class="mb-0">
                <small>&copy; {{ currentYear }} All Rights Reserved.</small>
            </p>
            <div class="mt-2">
                <a href="#home" class="text-white mx-2 text-decoration-none hover-link">Home</a>
                <a href="#services" class="text-white mx-2 text-decoration-none hover-link">Services</a>
                <a href="#gallery" class="text-white mx-2 text-decoration-none hover-link">Gallery</a>
                <a href="#contact" class="text-white mx-2 text-decoration-none hover-link">Contact</a>
            </div>
        </div>
    </footer>
</template>

<script setup>
const currentYear = new Date().getFullYear();
</script>

<style scoped>
.hover-link:hover {
    color: #ffd700 !important;
    /* Gold color on hover */
    transition: color 0.3s;
}
</style>
