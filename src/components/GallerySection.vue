<template>
    <section id="gallery" class="py-5 py-lg-6 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-4 fw-bold mb-3">Moments We've Created</h2>
                <p class="lead text-muted">A selection of our finest recent celebrations.</p>
            </div>

            <div class="row row-cols-1 row-cols-sm-2 row-cols-lg-3 g-3">
                <!-- Gallery Item 1 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom">
                        <img src="https://placehold.co/800x600/b0c4de/333333?text=Ceremony+Setup" alt="Ceremony Setup"
                            class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/b0c4de/333333?text=Image+Unavailable'">
                    </div>
                </div>
                <!-- Gallery Item 2 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom">
                        <img src="https://placehold.co/800x600/b0c4de/333333?text=Reception+Decor" alt="Reception Decor"
                            class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/b0c4de/333333?text=Image+Unavailable'">
                    </div>
                </div>
                <!-- Gallery Item 3 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom">
                        <img src="https://placehold.co/800x600/b0c4de/333333?text=Couple+Portrait" alt="Couple Portrait"
                            class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/b0c4de/333333?text=Image+Unavailable'">
                    </div>
                </div>
                <!-- Gallery Item 4 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom">
                        <img src="https://placehold.co/800x600/b0c4de/333333?text=Cake+Table" alt="Cake Table"
                            class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/b0c4de/333333?text=Image+Unavailable'">
                    </div>
                </div>
                <!-- Gallery Item 5 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom">
                        <img src="https://placehold.co/800x600/b0c4de/333333?text=Floral+Arrangement"
                            alt="Floral Arrangement" class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/b0c4de/333333?text=Image+Unavailable'">
                    </div>
                </div>
                <!-- Gallery Item 6 -->
                <div class="col">
                    <div class="ratio ratio-4x3 rounded-3 overflow-hidden shadow-lg hover-zoom">
                        <img src="https://placehold.co/800x600/b0c4de/333333?text=First+Dance" alt="First Dance"
                            class="img-fluid object-fit-cover" loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/800x600/b0c4de/333333?text=Image+Unavailable'">
                    </div>
                </div>
            </div>

            <div class="text-center mt-5">
                <a href="#contact" class="btn btn-outline-dark px-4 py-2 rounded-pill">View Full Portfolio</a>
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
</style>
