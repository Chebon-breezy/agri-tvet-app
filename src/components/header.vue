<!-- src/components/Header.vue -->
<template>
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
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped>
/* Add any additional styling for Header here */
</style>