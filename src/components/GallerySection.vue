<template>
    <section id="gallery" class="py-5 py-lg-6 bg-st-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-4 fw-bold mb-3">I Momenti Che Creiamo</h2>
                <p class="lead text-muted">Una selezione delle nostre celebrazioni più recenti.</p>
            </div>

            <div class="row row-cols-1 row-cols-sm-2 row-cols-lg-3 g-3">
                <!-- Gallery Item 1 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom position-relative">
                        <img src="/pranzo.jpg" alt="Allestimento Cerimonia" class="img-fluid object-fit-cover"
                            loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/fce8f2/333?text=Allestimento+Cerimonia'">
                        <!-- Overlay Text (Visible by default) -->
                        <div
                            class="gallery-caption position-absolute top-0 start-0 w-100 h-100 d-flex flex-column justify-content-center align-items-center text-white text-center p-3">
                            <h4 class="h5 fw-bold mb-0 gallery-text">Allestimento Cerimonia</h4>
                        </div>
                    </div>
                </div>
                <!-- Gallery Item 2 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom position-relative">
                        <img src="/pranzo.jpg" alt="Allestimento Ricevimento" class="img-fluid object-fit-cover"
                            loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/fce8f2/333?text=Allestimento+Ricevimento'">
                        <!-- Overlay Text (Visible by default) -->
                        <div
                            class="gallery-caption position-absolute top-0 start-0 w-100 h-100 d-flex flex-column justify-content-center align-items-center text-white text-center p-3">
                            <h4 class="h5 fw-bold mb-0 gallery-text">Allestimento Ricevimento</h4>
                        </div>
                    </div>
                </div>
                <!-- Gallery Item 3 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom position-relative">
                        <img src="/pranzo.jpg" alt="Ritratto degli Sposi" class="img-fluid object-fit-cover"
                            loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/fce8f2/333?text=Ritratto+degli+Sposi'">
                        <!-- Overlay Text (Visible by default) -->
                        <div
                            class="gallery-caption position-absolute top-0 start-0 w-100 h-100 d-flex flex-column justify-content-center align-items-center text-white text-center p-3">
                            <h4 class="h5 fw-bold mb-0 gallery-text">Ritratto degli Sposi</h4>
                        </div>
                    </div>
                </div>
                <!-- Gallery Item 4 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom position-relative">
                        <img src="/pranzo.jpg" alt="Tavolo della Torta" class="img-fluid object-fit-cover"
                            loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/fce8f2/333?text=Tavolo+della+Torta'">
                        <!-- Overlay Text (Visible by default) -->
                        <div
                            class="gallery-caption position-absolute top-0 start-0 w-100 h-100 d-flex flex-column justify-content-center align-items-center text-white text-center p-3">
                            <h4 class="h5 fw-bold mb-0 gallery-text">Il Tavolo della Torta</h4>
                        </div>
                    </div>
                </div>
                <!-- Gallery Item 5 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom position-relative">
                        <img src="/pranzo.jpg" alt="Composizione Floreale" class="img-fluid object-fit-cover"
                            loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/fce8f2/333?text=Composizione+Floreale'">
                        <!-- Overlay Text (Visible by default) -->
                        <div
                            class="gallery-caption position-absolute top-0 start-0 w-100 h-100 d-flex flex-column justify-content-center align-items-center text-white text-center p-3">
                            <h4 class="h5 fw-bold mb-0 gallery-text">Composizioni Floreali</h4>
                        </div>
                    </div>
                </div>
                <!-- Gallery Item 6 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom position-relative">
                        <img src="/pranzo.jpg" alt="Primo Ballo" class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/fce8f2/333?text=Primo+Ballo'">
                        <!-- Overlay Text (Visible by default) -->
                        <div
                            class="gallery-caption position-absolute top-0 start-0 w-100 h-100 d-flex flex-column justify-content-center align-items-center text-white text-center p-3">
                            <h4 class="h5 fw-bold mb-0 gallery-text">Primo Ballo</h4>
                        </div>
                    </div>
                </div>
            </div>

            <div class="text-center mt-5">
                <a href="#contact" class="btn btn-outline-st-primary px-4 py-2 rounded-pill fw-bold">Galleria
                    Completa</a>
            </div>
        </div>
    </section>
</template>

<script setup>
// No script logic
</script>

<style scoped>
.hover-zoom {
    transition: transform 0.4s ease;
    overflow: hidden;
}

.hover-zoom img {
    transition: transform 0.5s ease;
}

.hover-zoom:hover img {
    transform: scale(1.1);
}

/* Custom styles for the overlay text container */
.gallery-caption {
    /* Initially transparent background */
    background-color: transparent;
    transition: background-color 0.3s ease-in-out, border 0.3s ease-in-out;
    z-index: 2;
    padding: 1rem;
}

.hover-zoom:hover .gallery-caption {
    /* Hover applies the dark overlay and a white border */
    background-color: rgba(0, 0, 0, 0.65);
    border: 4px solid var(--st-light);
}

/* Apply text shadow to ensure text pops against image details */
.gallery-text {
    /* Use strong shadow for maximum readability against any background */
    text-shadow: 1px 1px 6px #000;
}
</style>
