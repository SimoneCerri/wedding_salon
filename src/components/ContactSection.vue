<template>
    <section id="contact" class="py-5 py-lg-6 bg-primary text-white">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="text-center mb-5">
                        <h2 class="display-4 fw-bold mb-3">Ready to Begin Planning?</h2>
                        <p class="lead">Let's schedule a complimentary consultation to discuss your vision.</p>
                    </div>

                    <form @submit.prevent="submitForm" class="p-4 p-md-5 bg-white text-dark rounded-4 shadow-lg">
                        <div class="mb-3">
                            <label for="name" class="form-label">Your Name</label>
                            <input type="text" class="form-control form-control-lg rounded-3" id="name"
                                placeholder="John Doe" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email Address</label>
                            <input type="email" class="form-control form-control-lg rounded-3" id="email"
                                placeholder="email@example.com" required>
                        </div>
                        <div class="mb-3">
                            <label for="date" class="form-label">Preferred Wedding Date (Approximate)</label>
                            <input type="date" class="form-control form-control-lg rounded-3" id="date">
                        </div>
                        <div class="mb-4">
                            <label for="details" class="form-label">Tell Us About Your Event</label>
                            <textarea class="form-control rounded-3" id="details" rows="4"
                                placeholder="Guest count, style preference, etc."></textarea>
                        </div>
                        <div class="d-grid">
                            <button type="submit" class="btn btn-dark btn-lg fw-bold py-3 rounded-pill">Send
                                Inquiry</button>
                        </div>
                    </form>

                    <div v-if="submitted" class="mt-4 p-3 text-center bg-success text-white rounded-3">
                        Thank you! We will be in touch within 24 hours.
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
