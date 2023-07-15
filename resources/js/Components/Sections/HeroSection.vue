<template>
  <section class="bg-green-500 dark:bg-gray-900 text-white py-16">
    <div class="container mx-auto">
      <div class="flex flex-col items-center justify-center">
        <img src="/path/to/fake-image.jpg" alt="Task Manager" class="w-32 h-32 rounded-full mb-4">
        <h1 class="text-4xl font-bold mb-4">Task Manager</h1>
        <p class="text-lg mb-8">Organize your tasks efficiently with our powerful task management app.</p>
        <a href="#" class="bg-green-700 text-white px-6 py-3 rounded-full font-bold hover:bg-green-900 transition duration-300 ease-in-out">Get Started</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
};
</script>

<style scoped>
.dark {
  background-color: #111827;
  color: #fff;
}
</style>
