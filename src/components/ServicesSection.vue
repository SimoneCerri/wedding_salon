<template>
    <section id="services" class="py-5 py-lg-6 bg-white">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-4 fw-bold mb-3">Our Signature Services</h2>
                <p class="lead text-muted">A perfect celebration is built on impeccable planning and dedication.</p>
            </div>

            <div class="row row-cols-1 row-cols-md-3 g-4">

                <!-- Service Card 1 -->
                <div class="col">
                    <div class="card h-100 shadow-sm border-0 rounded-4 transition-hover">
                        <div class="card-body p-4 text-center">
                            <h3 class="card-title h4 mb-3 text-dark">Full-Service Planning</h3>
                            <p class="card-text text-muted">From vendor selection to day-of coordination, we handle
                                every logistical detail of your grand day.</p>
                            <span class="badge bg-primary-subtle text-primary-emphasis rounded-pill px-3 py-2">Most
                                Popular</span>
                        </div>
                    </div>
                </div>

                <!-- Service Card 2 -->
                <div class="col">
                    <div class="card h-100 shadow-sm border-0 rounded-4 transition-hover">
                        <div class="card-body p-4 text-center">
                            <h3 class="card-title h4 mb-3 text-dark">Venue & Design</h3>
                            <p class="card-text text-muted">Transforming spaces into breathtaking settings that reflect
                                your unique love story and style.</p>
                            <span
                                class="badge bg-secondary-subtle text-secondary-emphasis rounded-pill px-3 py-2">Bespoke
                                Decor</span>
                        </div>
                    </div>
                </div>

                <!-- Service Card 3 -->
                <div class="col">
                    <div class="card h-100 shadow-sm border-0 rounded-4 transition-hover">
                        <div class="card-body p-4 text-center">
                            <h3 class="card-title h4 mb-3 text-dark">Catering Excellence</h3>
                            <p class="card-text text-muted">Gourmet menus crafted by our award-winning chefs, ensuring
                                an unforgettable culinary experience.</p>
                            <span class="badge bg-success-subtle text-success-emphasis rounded-pill px-3 py-2">Fine
                                Dining</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
// No script logic
</script>

<style scoped>
.transition-hover:hover {
    transform: translateY(-5px);
    box-shadow: 0 1rem 3rem rgba(0, 0, 0, .175) !important;
    transition: all 0.3s ease-in-out;
}
</style>
