<!-- src/components/Hero.vue -->
<template>
    <section class="bg-cover bg-center h-96" style="background-image: url('https://example.com/hero-image.jpg')">
        <div class="bg-black bg-opacity-50 h-full flex items-center justify-center">
            <div class="text-center text-white">
                <h1 class="text-4xl font-bold mb-4">Welcome to Ravine Agricultural Technical College</h1>
                <p class="text-xl">Empowering the next generation of agricultural experts</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Hero',
};
</script>

<style scoped>
/* Add any additional styling for Hero here */
</style>