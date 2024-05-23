<!-- src/App.vue -->
<template>
  <div class="min-h-screen bg-gray-100">
    <Header />
    <Hero />
    <main class="container mx-auto py-8">
      <section class="text-center mb-12">
        <h2 class="text-3xl font-bold mb-4">Our Programs</h2>
        <p class="text-lg">We offer a wide range of programs to suit your interests and career goals.</p>
      </section>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white shadow-lg rounded-lg overflow-hidden">
          <img src="https://example.com/program1.jpg" alt="Program 1" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-bold mb-2">Program Title 1</h3>
            <p class="text-gray-700 mb-4">Brief description of the program. Lorem ipsum dolor sit amet, consectetur
              adipiscing elit.</p>
            <a href="#" class="text-green-700 hover:underline">Learn more</a>
          </div>
        </div>
        <!-- Repeat similar blocks for other programs -->
        <div class="bg-white shadow-lg rounded-lg overflow-hidden">
          <img src="https://example.com/program1.jpg" alt="Program 2" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-bold mb-2">Program Title 2</h3>
            <p class="text-gray-700 mb-4">Brief description of the program. Lorem ipsum dolor sit amet, consectetur
              adipiscing elit.</p>
            <a href="#" class="text-green-700 hover:underline">Learn more</a>
          </div>
        </div>
        <div class="bg-white shadow-lg rounded-lg overflow-hidden">
          <img src="https://example.com/program1.jpg" alt="Program 3" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-bold mb-2">Program Title 3</h3>
            <p class="text-gray-700 mb-4">Brief description of the program. Lorem ipsum dolor sit amet, consectetur
              adipiscing elit.</p>
            <a href="#" class="text-green-700 hover:underline">Learn more</a>
          </div>
        </div>
      </div>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from './components/header.vue';
import Hero from './components/hero.vue';
import Footer from './components/footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Footer,
  },
};
</script>

<style scoped>
/* Add any additional styling here */
</style>
