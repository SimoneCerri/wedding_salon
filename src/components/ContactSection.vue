<template>
    <section id="contact" class="py-5 py-lg-6 bg-st-dark text-white">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="text-center mb-5 text-dark">
                        <h2 class="display-4 fw-bold mb-3">Pronti per iniziare a Pianificare?</h2>
                        <p class="lead">Fissiamo una consulenza gratuita per discutere la vostra visione.</p>
                    </div>

                    <form @submit.prevent="submitForm" class="p-4 p-md-5 bg-st-light text-st-dark rounded-4 shadow-lg">
                        <div class="mb-3">
                            <label for="name" class="form-label">Il Tuo Nome</label>
                            <input type="text" class="form-control form-control-lg rounded-3 border-st-primary"
                                id="name" placeholder="Mario Rossi" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Indirizzo Email</label>
                            <input type="email" class="form-control form-control-lg rounded-3 border-st-primary"
                                id="email" placeholder="email@esempio.com" required>
                        </div>
                        <div class="mb-3">
                            <label for="date" class="form-label">Data Preferita (Approssimativa)</label>
                            <input type="date" class="form-control form-control-lg rounded-3 border-st-primary"
                                id="date">
                        </div>
                        <div class="mb-4">
                            <label for="details" class="form-label">Parlaci del Vostro Evento</label>
                            <textarea class="form-control rounded-3 border-st-primary" id="details" rows="4"
                                placeholder="Numero invitati, stile desiderato, ecc."></textarea>
                        </div>
                        <div class="d-grid">
                            <button type="submit" class="btn btn-st-accent btn-lg fw-bold py-3 rounded-pill">Invia
                                Richiesta</button>
                        </div>
                    </form>

                    <div v-if="submitted" class="mt-4 p-3 text-center bg-success text-white rounded-3">
                        Grazie! Saremo in contatto entro 24 ore.
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
import { ref } from 'vue';

const submitted = ref(false);

const submitForm = () => {
    // In a real application, you would send this data to a backend API here.
    console.log("Form Submitted!");
    submitted.value = true;

    // Optionally reset the form after a delay
    setTimeout(() => {
        submitted.value = false;
        // Clear form inputs manually if needed
    }, 5000);
};
</script>

<style scoped>
.border-st-primary {
    border: 1px solid var(--st-primary) !important;
}

.form-control:focus {
    border-color: var(--st-accent) !important;
    box-shadow: 0 0 0 0.25rem rgba(247, 69, 69, 0.25) !important;
    /* Custom shadow using accent color */
}

h2 {
    padding: 0.5em 0;
    line-height: 2em;
}

button {
    border: 1px solid var(--st-primary);
    background-color: var(--st-light-bg);
}

.d-grid {
    display: flex;
    justify-content: center;
}
</style>
