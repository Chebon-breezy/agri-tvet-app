<!-- src/views/AboutUs.vue -->
<template>
    <div class="about-us bg-gray-100 min-h-screen">
        <Header />
        <section class="bg-white py-12">
            <div class="container mx-auto px-4">
                <h1 class="text-4xl font-bold mb-6 text-center">About Us</h1>
                <div class="text-lg text-gray-700 leading-relaxed">
                    <p class="mb-4">
                        Ravine Agricultural Technical College is dedicated to advancing the field of agriculture through
                        education, research, and community engagement. Our college offers a range of programs designed
                        to
                        prepare students for successful careers in agriculture and related industries.
                    </p>
                    <p class="mb-4">
                        Founded in 1950, our college has a rich history of fostering innovation and excellence in
                        agricultural
                        education. Our faculty consists of experienced professionals who are leaders in their fields and
                        are
                        committed to providing students with the knowledge and skills needed to thrive in today's
                        dynamic
                        agricultural landscape.
                    </p>
                    <p class="mb-4">
                        At Ravine Agricultural Technical College, we believe in a hands-on approach to learning. Our
                        state-of-the-art
                        facilities, including modern laboratories, research farms, and greenhouses, provide students
                        with
                        opportunities to apply their knowledge in real-world settings.
                    </p>
                    <p class="mb-4">
                        Our mission is to empower the next generation of agricultural experts through comprehensive
                        education,
                        practical experience, and community involvement. We strive to create a supportive and inclusive
                        environment where all students can achieve their full potential.
                    </p>
                    <p class="mb-4">
                        Join us at Ravine Agricultural Technical College and be a part of a vibrant community dedicated
                        to
                        making a positive impact on the future of agriculture.
                    </p>
                </div>
            </div>
        </section>
        <Footer />
    </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';

export default {
    name: 'AboutUs',
    components: {
        Header,
        Footer,
    },
};
</script>

<style scoped>
/* Add any additional styling here */
</style>