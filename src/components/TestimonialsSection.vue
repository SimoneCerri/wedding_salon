<template>
    <section id="testimonials" class="py-5 py-lg-6 bg-st-light-bg text-st-dark">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-4 fw-bold mb-3">Le Coppie Felici</h2>
                <div class="d-flex align-items-center justify-content-center">
                    <p class="lead text-muted">Non fidatevi solo della nostra parola: ascoltate chi si è fidato di noi.
                    </p>
                </div>

            </div>

            <div class="row row-cols-1 row-cols-md-3 g-4">

                <!-- Testimonial 1 -->
                <div class="col">
                    <div class="card h-100 shadow border-0 rounded-4 p-3 bg-st-light">
                        <div class="card-body">
                            <p class="fst-italic text-center mb-4">"Il team di Spoiler, Ti Sposo! ha superato ogni
                                aspettativa.
                                La loro attenzione ai dettagli è stata impeccabile, rendendo il nostro matrimonio
                                assolutamente perfetto e senza stress."</p>
                            <div class="text-center">
                                <p class="fw-bold mb-0">- Jack Skellington & Sally.</p>
                                <small class="text-muted">Matrimonio Primavera, 2024</small>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="col">
                    <div class="card h-100 shadow border-0 rounded-4 p-3 bg-st-light">
                        <div class="card-body">
                            <p class="fst-italic text-center mb-4">"Il design e l'allestimento della location erano
                                davvero
                                mozzafiato. Lo consiglio vivamente!"</p>
                            <div class="text-center">
                                <p class="fw-bold mb-0">- Tu ma e tu pa.</p>
                                <small class="text-muted">Celebrazione Autunnale, 2023</small>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 3 -->
                <div class="col">
                    <div class="card h-100 shadow border-0 rounded-4 p-3 bg-st-light">
                        <div class="card-body">
                            <p class="fst-italic text-center mb-4">"Professionali, calorosi e creativi. Hanno reso la
                                pianificazione divertente e hanno realizzato un giorno che sembrava unicamente nostro.
                                Cinque stelle!"</p>
                            <div class="text-center">
                                <p class="fw-bold mb-0">- Cugino & Cugina.</p>
                                <small class="text-muted">Evento Estivo, 2024</small>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>

</script>

<style scoped>
#testimonials {
    /* Using the light background color from the palette */
    background-color: var(--st-light-bg) !important;

    h2 {
        color: var(--st-light);
        margin-bottom: 2em !important;
    }

    .lead {
        color: var(--st-dark) !important;
        background-color: var(--st-light-bg);
        border: 1px solid var(--st-primary);
        max-width: 600px;
        border-radius: 10px;
        padding: 0.25em;
    }
}

.card {
    border: 1px solid var(--st-primary) !important;

    .card-body {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
}

/* Add custom background image reference if needed (assuming fedine.jpg is available)  */
#testimonials {
    background-image: url(/fedine.jpg);
    background-position: center;
    background-size: cover;
    background-position-y: -45em;

    @media screen {}
}
</style>
