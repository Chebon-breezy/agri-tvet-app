<template>
  <div class="min-h-screen bg-gray-100">
    <!-- Header -->
    <header class="bg-green-700 text-white py-4">
      <div class="container mx-auto flex justify-between items-center">
        <div class="text-2xl font-bold">Ravine Agricultural Technical College</div>
        <nav>
          <ul class="flex space-x-4">
            <li><a href="#" class="hover:text-gray-200">Home</a></li>
            <li><a href="#" class="hover:text-gray-200">About</a></li>
            <li><a href="#" class="hover:text-gray-200">Programs</a></li>
            <li><a href="#" class="hover:text-gray-200">Admissions</a></li>
            <li><a href="#" class="hover:text-gray-200">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-cover bg-center h-96" style="background-image: url('https://example.com/hero-image.jpg')">
      <div class="bg-black bg-opacity-50 h-full flex items-center justify-center">
        <div class="text-center text-white">
          <h1 class="text-4xl font-bold mb-4">Welcome to Ravine Agricultural Technical College</h1>
          <p class="text-xl">Empowering the next generation of agricultural experts</p>
        </div>
      </div>
    </section>

    <!-- Main Content -->
    <main class="container mx-auto py-8">
      <section class="text-center mb-12">
        <h2 class="text-3xl font-bold mb-4">Our Programs</h2>
        <p class="text-lg">We offer a wide range of programs to suit your interests and career goals.</p>
      </section>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Program Card -->
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
      </div>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
      <div class="container mx-auto text-center">
        <p>&copy; 2024 Ravine Agricultural Technical College. All rights reserved.</p>
        <p class="mt-2">1234 College Avenue, Ravine Town, Country | (123) 456-7890</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
/* Add any additional styling here */
</style>
