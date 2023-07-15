<template>
  <footer class="bg-gradient-to-b from-gray-900 to-gray-800 dark:text-white">
    <div class="container mx-auto px-4 py-8">
      <div class="flex flex-wrap justify-between">
        <div class="w-full md:w-1/2 lg:w-1/4 flex items-center">
          <img src="fake-logo.png" alt="Logo" class="w-24 h-24 mr-4" />
          
            <p class="text-neutral-500 dark:text-neutral-200 mb-4">
              Task Manager App is a powerful tool for managing your tasks and staying organized. Keep track of your daily tasks, set reminders, and accomplish your goals effortlessly.
            </p>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/4">
          <h4 class="text-lf font-semibold mb-4">Links</h4>
          <ul class="list-none">
              <li><a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">Home</a></li>
              <li><a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">About</a></li>
              <li><a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">Services</a></li>
              <li><a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">Contact</a></li>
            </ul>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/4">
          <h4 class="text-lg font-semibold mb-4">Social</h4>
          <ul class="flex list-none space-x-4">
            <li>
              <a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M12 5l7 7-7 7" />
                </svg>
              </a>
            </li>
            <li>
              <a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
              </a>
            </li>
            <li>
              <a href="#" class="text-neutral-500 dark:text-neutral-200 hover:text-green-500">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                </svg>
              </a>
            </li>
          </ul>
        </div>
      </div>
      <div class="text-center mt-8">
        <p class="text-neutral-500 dark:text-neutral-200">&copy; 2023 Task Manager App. All rights reserved.</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
};
</script>
