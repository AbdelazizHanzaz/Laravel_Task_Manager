<template>
  <section class="bg-gray-900 dark:text-white py-16">
    <div class="container mx-auto px-4">
      <div class="max-w-2xl mx-auto text-center">
        <h2 class="text-4xl font-bold mb-6">Subscribe to Our Newsletter</h2>
        <p class="mb-12 text-neutral-500 dark:text-neutral-200">
          Stay up to date with our latest news and updates.
        </p>
        <div class="w-3/4 mx-auto">
          <div class="flex flex-col md:flex-row items-center justify-center">
            <input
              type="email"
              placeholder="Enter your email"
              class="w-full md:w-80 rounded-lg border-gray-300 bg-gray-100 dark:bg-gray-800 px-4 py-2 mb-4 md:mb-0 md:mr-4 focus:border-green-500 focus:ring-green-500"
            />
            <button
              type="submit"
              class="bg-green-600 hover:bg-green-700 text-white font-bold py-3 px-6 rounded-lg"
            >
              Subscribe
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'NewsletterSection',
};
</script>
