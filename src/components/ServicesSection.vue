<template>
    <section id="services" class="py-5 py-lg-6 bg-st-light-bg text-st-dark">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-4 fw-bold mb-3">I Nostri Servizi "No-Cliché"</h2>
                <p class="lead text-muted">Una festa perfetta si costruisce con pianificazione impeccabile e passione.
                </p>
            </div>

            <div class="row row-cols-1 row-cols-md-3 g-4">

                <!-- Service Card 1: Pianificazione Completa -->
                <div class="col">
                    <div class="card h-100 shadow-sm border-0 rounded-4 transition-hover">
                        <div class="card-body p-4 text-center">
                            <h3 class="card-title h4 mb-3 text-st-dark">Pianificazione Completa</h3>
                            <p class="card-text text-muted">Dalla selezione dei fornitori al coordinamento del giorno,
                                gestiamo ogni dettaglio logistico del vostro grande giorno.</p>
                            <span class="badge bg-st-accent text-white rounded-pill px-3 py-2">Più Richiesto</span>
                        </div>
                    </div>
                </div>

                <!-- Service Card 2: Design e Allestimenti -->
                <div class="col">
                    <div class="card h-100 shadow-sm border-0 rounded-4 transition-hover">
                        <div class="card-body p-4 text-center">
                            <h3 class="card-title h4 mb-3 text-st-dark">Design e Allestimenti (Senza Cliché)</h3>
                            <p class="card-text text-muted">Trasformiamo gli spazi in scenari mozzafiato che riflettono
                                la
                                vostra storia d'amore e il vostro stile unico.</p>
                            <span class="badge bg-st-primary text-st-dark rounded-pill px-3 py-2">Allestimenti Su
                                Misura</span>
                        </div>
                    </div>
                </div>

                <!-- Service Card 3: Eccellenza Culinaria -->
                <div class="col">
                    <div class="card h-100 shadow-sm border-0 rounded-4 transition-hover">
                        <div class="card-body p-4 text-center">
                            <h3 class="card-title h4 mb-3 text-st-dark">Eccellenza Culinaria</h3>
                            <p class="card-text text-muted">Menù gourmet curati dai nostri chef, per un'esperienza
                                culinaria
                                indimenticabile.</p>
                            <span class="badge bg-st-primary text-st-dark rounded-pill px-3 py-2">Alta Cucina</span>
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
    border-color: var(--st-primary) !important;
}

h2 {
    padding: 0.5em 0;
}

h3 {
    padding: 1.5em;
    line-height: 2em;
}

.card {
    border: 1px solid var(--st-light-bg) !important;

    .card-body {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
}
</style>
