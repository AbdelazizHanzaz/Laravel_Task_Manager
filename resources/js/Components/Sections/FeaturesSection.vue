<template>
  <section class="bg-gray-900 dark:text-white py-16">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">Features</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-green-800 rounded-lg p-6 flex flex-col items-center">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-12 h-12 mb-4 text-green-500">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/>
          </svg>
          <div class="text-center">
            <h3 class="text-xl font-semibold mb-2">Task Tracking</h3>
            <p class="text-gray-300">Easily track and manage your tasks and to-do lists.</p>
          </div>
        </div>
        <div class="bg-green-800 rounded-lg p-6 flex flex-col items-center">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-12 h-12 mb-4 text-green-500">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
          </svg>
          <div class="text-center">
            <h3 class="text-xl font-semibold mb-2">Deadline Reminders</h3>
            <p class="text-gray-300">Set reminders for important deadlines and due dates.</p>
          </div>
        </div>
        <div class="bg-green-800 rounded-lg p-6 flex flex-col items-center">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-12 h-12 mb-4 text-green-500">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"/>
          </svg>
          <div class="text-center">
            <h3 class="text-xl font-semibold mb-2">Collaboration</h3>
            <p class="text-gray-300">Collaborate with your team members and share tasks easily.</p>
          </div>
        </div>
        <!-- Add more feature cards here -->
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FeaturesSection',
};
</script>
